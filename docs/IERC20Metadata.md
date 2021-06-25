# IERC20Metadata.sol

View Source: [openzeppelin-solidity/contracts/token/ERC20/extensions/IERC20Metadata.sol](../openzeppelin-solidity/contracts/token/ERC20/extensions/IERC20Metadata.sol)

**↗ Extends: [IERC20](IERC20.md)**
**↘ Derived Contracts: [ERC20](ERC20.md)**

**IERC20Metadata**

Interface for the optional metadata functions from the ERC20 standard.
 _Available since v4.1._

## Functions

- [name()](#name)
- [symbol()](#symbol)
- [decimals()](#decimals)

### name

Returns the name of the token.

```js
function name() external view
returns(string)
```

**Arguments**

| Name        | Type           | Description  |
| ------------- |------------- | -----|

### symbol

Returns the symbol of the token.

```js
function symbol() external view
returns(string)
```

**Arguments**

| Name        | Type           | Description  |
| ------------- |------------- | -----|

### decimals

Returns the decimals places of the token.

```js
function decimals() external view
returns(uint8)
```

**Arguments**

| Name        | Type           | Description  |
| ------------- |------------- | -----|

## Contracts

* [Address](Address.md)
* [Commission](Commission.md)
* [Context](Context.md)
* [Controller](Controller.md)
* [Cover](Cover.md)
* [CoverAssurance](CoverAssurance.md)
* [CoverBase](CoverBase.md)
* [CoverProvision](CoverProvision.md)
* [CoverStake](CoverStake.md)
* [CoverUtilV1](CoverUtilV1.md)
* [ERC20](ERC20.md)
* [Factory](Factory.md)
* [Governance](Governance.md)
* [ICommission](ICommission.md)
* [ICover](ICover.md)
* [ICoverAssurance](ICoverAssurance.md)
* [ICoverStake](ICoverStake.md)
* [IERC20](IERC20.md)
* [IERC20Metadata](IERC20Metadata.md)
* [IMember](IMember.md)
* [IPolicy](IPolicy.md)
* [IProtocol](IProtocol.md)
* [IStore](IStore.md)
* [IVault](IVault.md)
* [IVaultFactory](IVaultFactory.md)
* [NTransferUtilV2](NTransferUtilV2.md)
* [Ownable](Ownable.md)
* [Pausable](Pausable.md)
* [Protocol](Protocol.md)
* [ProtoUtilV1](ProtoUtilV1.md)
* [Recoverable](Recoverable.md)
* [ReentrancyGuard](ReentrancyGuard.md)
* [SafeERC20](SafeERC20.md)
* [SafeMath](SafeMath.md)
* [Vault](Vault.md)
* [VaultFactory](VaultFactory.md)
* [VaultPod](VaultPod.md)
* [Witness](Witness.md)