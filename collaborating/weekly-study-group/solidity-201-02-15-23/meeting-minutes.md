---
description: A recap of our Solidity 201 discussion
---

# ⌛ Meeting Minutes

### Links&#x20;

* [dappsys github](https://github.com/dapphub/dappsys)
* [OZ ERC20 contract](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC20/ERC20.sol)
* [solmate ERC20 contract](https://github.com/transmissions11/solmate/blob/main/src/tokens/ERC20.sol)
* [OZ ERC777 contract](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC777/ERC777.sol)
* [OZ ERC777 Deep Dive -- Kyle L](https://medium.com/coinmonks/deep-dive-openzeppelins-erc777-implementation-9db978ce1bea)
* [EVM Deep Dives pt 3 -- noxx](https://noxx.substack.com/p/evm-deep-dives-the-path-to-shadowy-3ea)
* [evm.codes](https://www.evm.codes/?fork=grayGlacier)
* [C3 Linearization](https://en.wikipedia.org/wiki/C3\_linearization)

#### Notable Notes

* If allowance is set to 256.max, the ERC20 contract does not decrease the allowance after an amount is spent
* ERC777 can combine the approve and transfer steps into a single transaction&#x20;
