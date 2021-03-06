# API Reference

## Bancor Protocol Contracts v0.5 \(beta\)

### Overview

The solidity version of the Bancor smart contracts is composed of many different components that work together to create the Bancor Network deployment.

The main contracts are the BancorNetwork contract \(entry point to the system\) and the different converter contracts \(implementation of liquidity pools and their reserves\).

### Upgradeability

All smart contract functions are public and all upgrades are opt-in. If significant improvements are made to the system a new version will be released. Token owners can choose between moving to the new system or staying in the old one. If possible, new versions will be backwards compatible and able to interact with the old versions.

### Language

The terms “reserves” and “connectors” have the same meaning throughout Bancor’s smart contract code and documentation. “Reserve ratio” and “connector weight” are also used interchangeably. “Connector balance” refers to the token inventories held in a Smart Token’s reserve.

### Warning

Bancor is a work in progress. Make sure you understand the risks before using it.

### Testing

#### Prerequisites

* node 10.16.0
* npm 6.9.0
* python 3.7.3
* web3.py 4.9.2

#### Installation

* `npm install`

#### Verification

* Verifying all the contracts:
  * `npm test 1` \(quick testing\)
  * `npm test 2` \(full coverage\)
* [Verifying the BancorFormula contract](https://github.com/bancorprotocol/docs/tree/1b2ecdadd4af09a787714471c151c248749895ed/ethereum-contracts/ethereum-api-reference/solidity/python/README.md)

#### [Utilities](https://github.com/bancorprotocol/docs/tree/1b2ecdadd4af09a787714471c151c248749895ed/ethereum-contracts/ethereum-api-reference/solidity/utils/README.md)

### Collaborators

* [**Yudi Levi**](https://github.com/yudilevi)
* [**Barak Manos**](https://github.com/barakman)
* [**Ilana Pinhas**](https://github.com/ilanapi)
* [**David Benchimol**](https://github.com/davidbancor)
* [**Or Dadosh**](https://github.com/ordd)
* [**Martin Holst Swende**](https://github.com/holiman)

### License

Bancor Protocol is open source and distributed under the Apache License v2.0

