# Personal Diamonds Project

### What is a Diamond?

A diamond is a contract that implements the Diamond Standard.

Information about diamonds and the Diamond Standard:

* [ERC2535 Diamond Standard](https://github.com/ethereum/EIPs/issues/2535)
* [Understanding Diamonds on Ethereum](https://dev.to/mudgen/understanding-diamonds-on-ethereum-1fb)
* [Ethereum's Maximum Contract Size Limit is Solved with the Diamond Standard](https://dev.to/mudgen/ethereum-s-maximum-contract-size-limit-is-solved-with-the-diamond-standard-2189)

### What is a Personal Diamond?

A personal diamond is an upgradeable diamond that is owned and controlled by an end user. 

Only the owner of a personal diamond can upgrade their diamond, or give signed approval to do so.

Because diamonds can be unlimited in size it is possible to add/replace/remove any amount of functionality from them via facets.

A new contract storage technique called [Diamond Storage](https://medium.com/1milliondevs/new-storage-layout-for-proxy-contracts-and-diamonds-98d01d0eadb) makes it possible for facets to be independent from each other. 

Diamond Storage also makes possible the standardization of contract storage that is shared by different facets.

What this means is that an end user can have a personal diamond that only contains the contract functionality the user wants.

And it means that facets can be deployed once and be used by any number of different personal diamonds.

A personal diamond is a smart contract so it can integrate with other contracts on the network.

So for example a user could use a personal diamond to store Ether or tokens or integrate with a savings contract or other DeFi contract. A personal diamond can do anything that contracts can do.

The purpose of a personal diamond is to give users contract functionality they want and give them user interfaces to take actions they want to take.

## User Interface

The Personal Diamond project will create a user interface that enables users to create their own personal diamonds. The user interface will provide a set of different facets that users can choose from for adding different functionality to their personal diamonds.

The idea is to find out what people want to do on blockchains, then write facets that do those things, then provide those facets in the user interface so users can choose to add them to their personal diamonds. In addition, additional user interface functionality will be implemented to enable users to interact with and use the different facets that are available.

## Blockchains

The Personal Diamond project will be implemented on the Ethereum network and other networks and blockchains that can support diamonds.

## Third Parties

It is possible for projects outside the Personal Diamond project to also create facets and user interfaces for personal diamonds.

People can also join the Personal Diamond project to create new facets and user interfaces.



