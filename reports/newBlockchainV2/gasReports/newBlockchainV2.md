# Table of contents

- **[[0x0] Disclaimer](#0x0)**
- **[[G-01] External vs Public functions](#G-01)**

<br/>

## Disclaimer<a name="0x0"></a>
- Please, consider everything described below as a general recommendation. These notes will represent potential possibilities to optimize gas consumption. It's okay, if something is not suitable in your case. Just let me know the reason in the comments section. Enjoy!

<br/>

## [G-01] External vs Public functions<a name="G-01"></a>

### **PROBLEM**

- External functions allow to read directly from calldata, meanwhile public functions need to allocate the space in the memory for arguments. 

### **PROOF OF CONCEPT**

```Solidity
  - setAccountantContract(address) should be declared external 
    contracts/CNote.sol#L16-L21

  - RetAccountant() should be declared external
    contracts/Note.sol#L17-L19

  - delegateToViewImplementation(bytes) should be declared external
    contracts/Accountant/AccountantDelegator.sol#L107-L115

  - initialize(address) should be declared external
    contracts/Treasury/TreasuryDelegate.sol#L19-L27

  - delegate(address) should be declared external
    contracts/Governance/Comp.sol#L148-L150

  - delegateBySig(address,uint256,uint256,uint8,bytes32,bytes32) should be declared external
    contracts/Governance/Comp.sol#L161-L170

  - getPriorVotes(address,uint256) should be declared external
     contracts/Governance/Comp.sol#L189-L221 
  ```

### **TOOLS USED**
- Gasol-Optimizer
- Manual Analysis

### **MITIGATION**
- Remove the whole presence of the SafeMath. 
- It also includes replacing all SafeMath functions by solidity arithmetic operators.  

<br/>
