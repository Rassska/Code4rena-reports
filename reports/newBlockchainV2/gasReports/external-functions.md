Summary
 - [external-function](#external-function) (81 results) (Optimization)
## external-function
Impact: Optimization
Confidence: High
 - [ ] ID-0
approve(address,uint256) should be declared external:
	- [Token.approve(address,uint256)](contracts/Stableswap/test/Token.sol#L53-L57)

contracts/Stableswap/test/Token.sol#L53-L57


 - [ ] ID-1
transfer(address,uint256) should be declared external:
	- [Token.transfer(address,uint256)](contracts/Stableswap/test/Token.sol#L105-L107)

contracts/Stableswap/test/Token.sol#L105-L107


 - [ ] ID-2
transferFrom(address,address,uint256) should be declared external:
	- [Token.transferFrom(address,address,uint256)](contracts/Stableswap/test/Token.sol#L109-L119)

contracts/Stableswap/test/Token.sol#L109-L119


 - [ ] ID-3
getActions(uint256) should be declared external:
	- [GovernorAlpha.getActions(uint256)](contracts/Governance/GovernorAlpha.sol#L218-L221)

contracts/Governance/GovernorAlpha.sol#L218-L221


 - [ ] ID-4
castVote(uint256,bool) should be declared external:
	- [GovernorAlpha.castVote(uint256,bool)](contracts/Governance/GovernorAlpha.sol#L249-L251)

contracts/Governance/GovernorAlpha.sol#L249-L251


 - [ ] ID-5
castVoteBySig(uint256,bool,uint8,bytes32,bytes32) should be declared external:
	- [GovernorAlpha.castVoteBySig(uint256,bool,uint8,bytes32,bytes32)](contracts/Governance/GovernorAlpha.sol#L253-L260)

contracts/Governance/GovernorAlpha.sol#L253-L260


 - [ ] ID-6
__queueSetTimelockPendingAdmin(address,uint256) should be declared external:
	- [GovernorAlpha.__queueSetTimelockPendingAdmin(address,uint256)](contracts/Governance/GovernorAlpha.sol#L292-L295)

contracts/Governance/GovernorAlpha.sol#L292-L295


 - [ ] ID-7
cancel(uint256) should be declared external:
	- [GovernorAlpha.cancel(uint256)](contracts/Governance/GovernorAlpha.sol#L203-L216)

contracts/Governance/GovernorAlpha.sol#L203-L216


 - [ ] ID-8
queue(uint256) should be declared external:
	- [GovernorAlpha.queue(uint256)](contracts/Governance/GovernorAlpha.sol#L177-L186)

contracts/Governance/GovernorAlpha.sol#L177-L186


 - [ ] ID-9
__abdicate() should be declared external:
	- [GovernorAlpha.__abdicate()](contracts/Governance/GovernorAlpha.sol#L287-L290)

contracts/Governance/GovernorAlpha.sol#L287-L290


 - [ ] ID-10
execute(uint256) should be declared external:
	- [GovernorAlpha.execute(uint256)](contracts/Governance/GovernorAlpha.sol#L193-L201)

contracts/Governance/GovernorAlpha.sol#L193-L201


 - [ ] ID-11
propose(address[],uint256[],string[],bytes[],string) should be declared external:
	- [GovernorAlpha.propose(address[],uint256[],string[],bytes[],string)](contracts/Governance/GovernorAlpha.sol#L136-L175)

contracts/Governance/GovernorAlpha.sol#L136-L175


 - [ ] ID-12
__executeSetTimelockPendingAdmin(address,uint256) should be declared external:
	- [GovernorAlpha.__executeSetTimelockPendingAdmin(address,uint256)](contracts/Governance/GovernorAlpha.sol#L297-L300)

contracts/Governance/GovernorAlpha.sol#L297-L300


 - [ ] ID-13
getReceipt(uint256,address) should be declared external:
	- [GovernorAlpha.getReceipt(uint256,address)](contracts/Governance/GovernorAlpha.sol#L223-L225)

contracts/Governance/GovernorAlpha.sol#L223-L225


 - [ ] ID-14
__acceptAdmin() should be declared external:
	- [GovernorAlpha.__acceptAdmin()](contracts/Governance/GovernorAlpha.sol#L282-L285)

contracts/Governance/GovernorAlpha.sol#L282-L285


 - [ ] ID-15
_setPauseGuardian(address) should be declared external:
	- [Comptroller._setPauseGuardian(address)](contracts/Comptroller.sol#L1038-L1053)

contracts/Comptroller.sol#L1038-L1053


 - [ ] ID-16
_setCompSpeed(CToken,uint256) should be declared external:
	- [ComptrollerG7._setCompSpeed(CToken,uint256)](contracts/ComptrollerG7.sol#L1291-L1294)

contracts/ComptrollerG7.sol#L1291-L1294


 - [ ] ID-17
claimComp(address) should be declared external:
	- [ComptrollerG7.claimComp(address)](contracts/ComptrollerG7.sol#L1210-L1212)

contracts/ComptrollerG7.sol#L1210-L1212


 - [ ] ID-18
_become(Unitroller) should be declared external:
	- [Comptroller._become(Unitroller)](contracts/Comptroller.sol#L1093-L1096)

contracts/Comptroller.sol#L1093-L1096


 - [ ] ID-19
_become(Unitroller) should be declared external:
	- [ComptrollerG7._become(Unitroller)](contracts/ComptrollerG7.sol#L1046-L1049)

contracts/ComptrollerG7.sol#L1046-L1049


 - [ ] ID-20
withdraw(uint256) should be declared external:
	- [WETH.withdraw(uint256)](contracts/WETH.sol#L28-L33)

contracts/WETH.sol#L28-L33


 - [ ] ID-21
_grantComp(address,uint256) should be declared external:
	- [Comptroller._grantComp(address,uint256)](contracts/Comptroller.sol#L1399-L1404)

contracts/Comptroller.sol#L1399-L1404


 - [ ] ID-22
_setBorrowPaused(CToken,bool) should be declared external:
	- [Comptroller._setBorrowPaused(CToken,bool)](contracts/Comptroller.sol#L1065-L1073)

contracts/Comptroller.sol#L1065-L1073


 - [ ] ID-23
delegateBySig(address,uint256,uint256,uint8,bytes32,bytes32) should be declared external:
	- [Comp.delegateBySig(address,uint256,uint256,uint8,bytes32,bytes32)](contracts/Governance/Comp.sol#L161-L170)

contracts/Governance/Comp.sol#L161-L170


 - [ ] ID-24
enterMarkets(address[]) should be declared external:
	- [Comptroller.enterMarkets(address[])](contracts/Comptroller.sol#L127-L138)
	- [ComptrollerG7.enterMarkets(address[])](contracts/ComptrollerG7.sol#L112-L123)

contracts/Comptroller.sol#L127-L138


 - [ ] ID-25
getAccountLiquidity(address) should be declared external:
	- [ComptrollerG7.getAccountLiquidity(address)](contracts/ComptrollerG7.sol#L661-L665)

contracts/ComptrollerG7.sol#L661-L665


 - [ ] ID-26
cancelTransaction(address,uint256,string,bytes,uint256) should be declared external:
	- [Timelock.cancelTransaction(address,uint256,string,bytes,uint256)](contracts/Timelock.sol#L72-L79)

contracts/Timelock.sol#L72-L79


 - [ ] ID-27
_setCompSpeeds(CToken[],uint256[],uint256[]) should be declared external:
	- [Comptroller._setCompSpeeds(CToken[],uint256[],uint256[])](contracts/Comptroller.sol#L1412-L1421)

contracts/Comptroller.sol#L1412-L1421


 - [ ] ID-28
_setPendingImplementation(address) should be declared external:
	- [Unitroller._setPendingImplementation(address)](contracts/Unitroller.sol#L39-L52)

contracts/Unitroller.sol#L39-L52


 - [ ] ID-29
decimals() should be declared external:
	- [ERC20.decimals()](contracts/ERC20.sol#L65-L67)

contracts/ERC20.sol#L65-L67


 - [ ] ID-30
getAllMarkets() should be declared external:
	- [ComptrollerG7.getAllMarkets()](contracts/ComptrollerG7.sol#L1322-L1324)

contracts/ComptrollerG7.sol#L1322-L1324


 - [ ] ID-31
approve(address,uint256) should be declared external:
	- [ERC20.approve(address,uint256)](contracts/ERC20.sol#L114-L118)
	- [WETH.approve(address,uint256)](contracts/WETH.sol#L55-L59)

contracts/ERC20.sol#L114-L118


 - [ ] ID-32
_setSeizePaused(bool) should be declared external:
	- [Comptroller._setSeizePaused(bool)](contracts/Comptroller.sol#L1084-L1091)

contracts/Comptroller.sol#L1084-L1091


 - [ ] ID-33
setDirectPrice(address,uint256) should be declared external:
	- [SimplePriceOracle.setDirectPrice(address,uint256)](contracts/SimplePriceOracle.sol#L31-L34)

contracts/SimplePriceOracle.sol#L31-L34


 - [ ] ID-34
getAllMarkets() should be declared external:
	- [Comptroller.getAllMarkets()](contracts/Comptroller.sol#L1449-L1451)

contracts/Comptroller.sol#L1449-L1451


 - [ ] ID-35
getPriorVotes(address,uint256) should be declared external:
	- [Comp.getPriorVotes(address,uint256)](contracts/Governance/Comp.sol#L189-L221)

contracts/Governance/Comp.sol#L189-L221


 - [ ] ID-36
setAccountantContract(address) should be declared external:
	- [CNote.setAccountantContract(address)](contracts/CNote.sol#L16-L21)

contracts/CNote.sol#L16-L21


 - [ ] ID-37
initialize(address) should be declared external:
	- [TreasuryDelegate.initialize(address)](contracts/Treasury/TreasuryDelegate.sol#L19-L27)

contracts/Treasury/TreasuryDelegate.sol#L19-L27


 - [ ] ID-38
decreaseAllowance(address,uint256) should be declared external:
	- [ERC20.decreaseAllowance(address,uint256)](contracts/ERC20.sol#L180-L187)

contracts/ERC20.sol#L180-L187


 - [ ] ID-39
_setTransferPaused(bool) should be declared external:
	- [ComptrollerG7._setTransferPaused(bool)](contracts/ComptrollerG7.sol#L1028-L1035)

contracts/ComptrollerG7.sol#L1028-L1035


 - [ ] ID-40
_setMintPaused(CToken,bool) should be declared external:
	- [ComptrollerG7._setMintPaused(CToken,bool)](contracts/ComptrollerG7.sol#L1008-L1016)

contracts/ComptrollerG7.sol#L1008-L1016


 - [ ] ID-41
_setPendingAdmin(address) should be declared external:
	- [Unitroller._setPendingAdmin(address)](contracts/Unitroller.sol#L86-L102)

contracts/Unitroller.sol#L86-L102


 - [ ] ID-42
symbol() should be declared external:
	- [ERC20.symbol()](contracts/ERC20.sol#L48-L50)

contracts/ERC20.sol#L48-L50


 - [ ] ID-43
increaseAllowance(address,uint256) should be declared external:
	- [ERC20.increaseAllowance(address,uint256)](contracts/ERC20.sol#L160-L164)

contracts/ERC20.sol#L160-L164


 - [ ] ID-44
_setTransferPaused(bool) should be declared external:
	- [Comptroller._setTransferPaused(bool)](contracts/Comptroller.sol#L1075-L1082)

contracts/Comptroller.sol#L1075-L1082


 - [ ] ID-45
_setContributorCompSpeed(address,uint256) should be declared external:
	- [ComptrollerG7._setContributorCompSpeed(address,uint256)](contracts/ComptrollerG7.sol#L1301-L1315)

contracts/ComptrollerG7.sol#L1301-L1315


 - [ ] ID-46
_setPriceOracle(PriceOracle) should be declared external:
	- [Comptroller._setPriceOracle(PriceOracle)](contracts/Comptroller.sol#L831-L847)

contracts/Comptroller.sol#L831-L847


 - [ ] ID-47
getAccountLiquidity(address) should be declared external:
	- [Comptroller.getAccountLiquidity(address)](contracts/Comptroller.sol#L682-L686)

contracts/Comptroller.sol#L682-L686


 - [ ] ID-48
_setMintPaused(CToken,bool) should be declared external:
	- [Comptroller._setMintPaused(CToken,bool)](contracts/Comptroller.sol#L1055-L1063)

contracts/Comptroller.sol#L1055-L1063


 - [ ] ID-49
_acceptAdmin() should be declared external:
	- [Unitroller._acceptAdmin()](contracts/Unitroller.sol#L109-L129)

contracts/Unitroller.sol#L109-L129


 - [ ] ID-50
setUnderlyingPrice(CToken,uint256) should be declared external:
	- [SimplePriceOracle.setUnderlyingPrice(CToken,uint256)](contracts/SimplePriceOracle.sol#L25-L29)

contracts/SimplePriceOracle.sol#L25-L29


 - [ ] ID-51
_setSeizePaused(bool) should be declared external:
	- [ComptrollerG7._setSeizePaused(bool)](contracts/ComptrollerG7.sol#L1037-L1044)

contracts/ComptrollerG7.sol#L1037-L1044


 - [ ] ID-52
queueTransaction(address,uint256,string,bytes,uint256) should be declared external:
	- [Timelock.queueTransaction(address,uint256,string,bytes,uint256)](contracts/Timelock.sol#L61-L70)

contracts/Timelock.sol#L61-L70


 - [ ] ID-53
_grantComp(address,uint256) should be declared external:
	- [ComptrollerG7._grantComp(address,uint256)](contracts/ComptrollerG7.sol#L1279-L1284)

contracts/ComptrollerG7.sol#L1279-L1284


 - [ ] ID-54
initialize(address) should be declared external:
	- [GovernorBravoDelegate.initialize(address)](contracts/Governance/GovernorBravoDelegate.sol#L24-L31)

contracts/Governance/GovernorBravoDelegate.sol#L24-L31


 - [ ] ID-55
_setInterestRateModel(InterestRateModel) should be declared external:
	- [CErc20Delegator._setInterestRateModel(InterestRateModel)](contracts/CErc20Delegator.sol#L409-L412)
	- [CToken._setInterestRateModel(InterestRateModel)](contracts/CToken.sol#L1083-L1087)

contracts/CErc20Delegator.sol#L409-L412


 - [ ] ID-56
_setPriceOracle(PriceOracle) should be declared external:
	- [ComptrollerG7._setPriceOracle(PriceOracle)](contracts/ComptrollerG7.sol#L810-L826)

contracts/ComptrollerG7.sol#L810-L826


 - [ ] ID-57
acceptAdmin() should be declared external:
	- [Timelock.acceptAdmin()](contracts/Timelock.sol#L46-L52)

contracts/Timelock.sol#L46-L52


 - [ ] ID-58
name() should be declared external:
	- [ERC20.name()](contracts/ERC20.sol#L40-L42)

contracts/ERC20.sol#L40-L42


 - [ ] ID-59
drip() should be declared external:
	- [Reservoir.drip()](contracts/Reservoir.sol#L46-L67)

contracts/Reservoir.sol#L46-L67


 - [ ] ID-60
RetAccountant() should be declared external:
	- [Note.RetAccountant()](contracts/Note.sol#L17-L19)

contracts/Note.sol#L17-L19


 - [ ] ID-61
claimComp(address) should be declared external:
	- [Comptroller.claimComp(address)](contracts/Comptroller.sol#L1329-L1331)

contracts/Comptroller.sol#L1329-L1331


 - [ ] ID-62
totalSupply() should be declared external:
	- [ERC20.totalSupply()](contracts/ERC20.sol#L72-L74)
	- [WETH.totalSupply()](contracts/WETH.sol#L46-L48)

contracts/ERC20.sol#L72-L74


 - [ ] ID-63
_acceptImplementation() should be declared external:
	- [Unitroller._acceptImplementation()](contracts/Unitroller.sol#L59-L77)

contracts/Unitroller.sol#L59-L77


 - [ ] ID-64
getAccountLimits(ComptrollerLensInterface,address) should be declared external:
	- [CompoundLens.getAccountLimits(ComptrollerLensInterface,address)](contracts/Lens/CompoundLens.sol#L240-L249)

contracts/Lens/CompoundLens.sol#L240-L249


 - [ ] ID-65
_setPauseGuardian(address) should be declared external:
	- [ComptrollerG7._setPauseGuardian(address)](contracts/ComptrollerG7.sol#L991-L1006)

contracts/ComptrollerG7.sol#L991-L1006


 - [ ] ID-66
_resignImplementation() should be declared external:
	- [CDaiDelegate._resignImplementation()](contracts/CDaiDelegate.sol#L73-L93)
	- [CErc20Delegate._resignImplementation()](contracts/CErc20Delegate.sol#L36-L43)

contracts/CDaiDelegate.sol#L73-L93


 - [ ] ID-67
delegate(address) should be declared external:
	- [Comp.delegate(address)](contracts/Governance/Comp.sol#L148-L150)

contracts/Governance/Comp.sol#L148-L150


 - [ ] ID-68
_setContributorCompSpeed(address,uint256) should be declared external:
	- [Comptroller._setContributorCompSpeed(address,uint256)](contracts/Comptroller.sol#L1428-L1442)

contracts/Comptroller.sol#L1428-L1442


 - [ ] ID-69
getHypotheticalAccountLiquidity(address,address,uint256,uint256) should be declared external:
	- [Comptroller.getHypotheticalAccountLiquidity(address,address,uint256,uint256)](contracts/Comptroller.sol#L708-L715)

contracts/Comptroller.sol#L708-L715


 - [ ] ID-70
transfer(address,uint256) should be declared external:
	- [ERC20.transfer(address,uint256)](contracts/ERC20.sol#L91-L95)
	- [WETH.transfer(address,uint256)](contracts/WETH.sol#L61-L63)

contracts/ERC20.sol#L91-L95


 - [ ] ID-71
delegateToViewImplementation(bytes) should be declared external:
	- [AccountantDelegator.delegateToViewImplementation(bytes)](contracts/Accountant/AccountantDelegator.sol#L107-L115)

contracts/Accountant/AccountantDelegator.sol#L107-L115


 - [ ] ID-72
getHypotheticalAccountLiquidity(address,address,uint256,uint256) should be declared external:
	- [ComptrollerG7.getHypotheticalAccountLiquidity(address,address,uint256,uint256)](contracts/ComptrollerG7.sol#L687-L694)

contracts/ComptrollerG7.sol#L687-L694


 - [ ] ID-73
setWETHAddress(address) should be declared external:
	- [Comptroller.setWETHAddress(address)](contracts/Comptroller.sol#L1479-L1482)

contracts/Comptroller.sol#L1479-L1482


 - [ ] ID-74
getUnderlyingPrice(CToken) should be declared external:
	- [SimplePriceOracle.getUnderlyingPrice(CToken)](contracts/SimplePriceOracle.sol#L21-L23)

contracts/SimplePriceOracle.sol#L21-L23


 - [ ] ID-75
executeTransaction(address,uint256,string,bytes,uint256) should be declared external:
	- [Timelock.executeTransaction(address,uint256,string,bytes,uint256)](contracts/Timelock.sol#L81-L106)

contracts/Timelock.sol#L81-L106


 - [ ] ID-76
setDelay(uint256) should be declared external:
	- [Timelock.setDelay(uint256)](contracts/Timelock.sol#L37-L44)

contracts/Timelock.sol#L37-L44


 - [ ] ID-77
repayBehalf(address) should be declared external:
	- [Maximillion.repayBehalf(address)](contracts/Maximillion.sol#L28-L30)

contracts/Maximillion.sol#L28-L30


 - [ ] ID-78
_becomeImplementation(bytes) should be declared external:
	- [CDaiDelegate._becomeImplementation(bytes)](contracts/CDaiDelegate.sol#L31-L36)
	- [CErc20Delegate._becomeImplementation(bytes)](contracts/CErc20Delegate.sol#L21-L31)

contracts/CDaiDelegate.sol#L31-L36


 - [ ] ID-79
setPendingAdmin(address) should be declared external:
	- [Timelock.setPendingAdmin(address)](contracts/Timelock.sol#L54-L59)

contracts/Timelock.sol#L54-L59


 - [ ] ID-80
_setBorrowPaused(CToken,bool) should be declared external:
	- [ComptrollerG7._setBorrowPaused(CToken,bool)](contracts/ComptrollerG7.sol#L1018-L1026)

contracts/ComptrollerG7.sol#L1018-L1026


