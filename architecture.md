# Architecture

## Principles
Considering our values, all source code should be open source and available on most free license.

The platform should be modular and easily extendable.

## Ecosystem elements
We aim for a wide and open ecosystem, which initially will consist of:
1. Blockchain full nodes
2. Light validator node
3. Client wallet modules for each currency
4. Basic wallet that will integrate client wallet modules
5. Blockchain transaction explorer with market, validator and user statistics and scores.

Later can be added:
1. Smart wallets and portfolio managers
2. Seamless exhange gateways
3. Seamless multicurrency payment processors

## Tools

As an initial base, [Quorum](https://github.com/atomchaneg/quorum) can be used for first proof of concept.

DPoS consesus and open economic model will be implemented as a smart contract (quorum moved consesus onto smart contract level).

For the ethereum family chains we need to implement smart contract templates for validators.

For the bitcoin family exchange should be performed with multisig wallets. 
