# About : 
An Ethereum Dapp that support transferring of ownership, product auditing, and supply chain management.\
Project built using Truffle and solidity. 

# Used Libraries

| Library       | Version       |
| ------------- | ------------- |
 | "@openzeppelin/contracts" | "^2.5.1" |
  |  "@truffle/hdwallet-provider" | "^1.2.6" | 
   | "bignumber.js" | "^9.0.1" |
     | "truffle-assertions" | "^0.9.2" | 
    | "truffle-hdwallet-provider" | "^1.0.17" |

## Install

This repository contains Smart Contract code in Solidity (using Truffle), tests (also using Truffle), dApp scaffolding (using HTML, CSS and JS) and server app scaffolding.

To install, download or clone the repo, then:

`npm install`
`truffle compile`

## Develop Client

To run truffle tests:

`truffle test ./test/flightSurety.js`
`truffle test ./test/oracles.js`

To use the dapp:

`truffle migrate`
`npm run dapp`

To view dapp:

`http://localhost:8000`

## Develop Server

`npm run server`
`truffle test ./test/oracles.js`

## Deploy

To build dapp for prod:
`npm run dapp:prod`

Deploy the contents of the ./dapp folder


## Resources

* [How does Ethereum work anyway?](https://medium.com/@preethikasireddy/how-does-ethereum-work-anyway-22d1df506369)
* [BIP39 Mnemonic Generator](https://iancoleman.io/bip39/)
* [Truffle Framework](http://truffleframework.com/)
* [Ganache Local Blockchain](http://truffleframework.com/ganache/)
* [Remix Solidity IDE](https://remix.ethereum.org/)
* [Solidity Language Reference](http://solidity.readthedocs.io/en/v0.4.24/)
* [Ethereum Blockchain Explorer](https://etherscan.io/)
* [Web3Js Reference](https://github.com/ethereum/wiki/wiki/JavaScript-API)
>>>>>>> 4b5d810... init
# flightsurety_dapp
