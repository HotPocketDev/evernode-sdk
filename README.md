# Evernode SDK

Evernode SDK consists of libraries and tools required to develop and deploy HotPocket smart contracts on Evernode. This repo is used to provide early access to libraries and tools that are work-in-progress and get feedback.

## HotPocket

HotPocket is the smart contract execution and consensus engine of Evernode. HotPocket smart contracts can be developed using any POSIX-compliant language/framework. You can also develop client applications that interact with HotPocket smart contracts using web sockets. Please go through following material to gain and understanding of HotPocket development.

1. [HotPocket tutorial](hotpocket/tutorial.md) - Explains the journey of developing a HotPocket smart contract.

### HotPocket smart contract development

- [NodeJs library](https://www.npmjs.com/package/hotpocket-nodejs-contract) ([source](https://github.com/HotPocketDev/hp-nodejs-contract))
- [C library source](https://github.com/HotPocketDev/hp-c-contract)


### HotPocket client development

- [Javascript library](https://www.npmjs.com/package/hotpocket-js-client) for nodejs and browser. ([source](https://github.com/HotPocketDev/hp-js-client))


### HotPocket developer kit

To make it easy to get started and test HotPocket smart contracts on your local PC, you can use [HotPocket developer kit](hotpocket/hpdevkit.md).

## Evernode interactions

You need to interact with Evernode (via XRPL) to deploy your contracts on Evernode network. We will be introducing the necessary tools and libraries for that in the future.
