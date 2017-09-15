# Multiblockchain interaction platform

We believe blockchain ecosystem have a unavoidable need for multiblockchain interaction platforms in order to make a next step and the development of the industry.

At he moment there are tens of very advanced distributed blockchain platforms but there is no way to interact for them except through centralized platforms.

All the centralized exchanges bears full pack of respective risks and inconvenience connected with central point of attack and control.

Our goal is to make an open, easily extandable platform and standard for multiblockchain interaction. We do not want to work several years on something that will turn out impractical. We want to implement the system step by step in short milestones that would be usable by community by themselves. 

## Exchange Roadmap

First and most important use case of multiblockchain interaction is a token exchange.

Considering iterative approach, the first sevaral milestones would be:
1. FTT to ETH exchange
2. FTT to BTC token exchange
3. BTC to ETH exchange
4. Add more pairs

In this list there is 2 families of blockchains mentioned: bitcoin-based and ethereum-based.

Both of these families will require slightly different approach but in both cases secure decentralized exchange can be implemented.

## Validator

Anyone can join as a validator to the network.

Validator have no custody of funds.

Validator provides his signature on both sides of the deal when both parties released funds. 

Validator can charge a fee on each validated exchange. 

## FTT to ETH exchange

Both networks are ethereum-family. 

Validator participation can be implemented via smart contract that acts in a similar way of multisig address. 

There are two contracts created on FreeTeal network and Ethereum network. 

Each contract receives funds from sender.

As soon as each contracted credited with pre-agreed amount of tokens, Validator puts its signature and receiving side can claim newly acquired tokens

## FTT to BTC exchange

FreeTeal network exchange implemented via smart contract, descibed above.
Bitcoin network exchange implemented via 2of3 multisig address on the bitcoin network with signing right from the Validator. 

## BTC to ETH exchange

After both of above case are implemented, BTC to ETH exchange also becomes possible. 

## Orderbook

Global Orderbook is kept in FreeTeal blockchain. 

Considering that FreeTeal is a DPoS system, we can achieve tolerable speed for the initial phase of the project. 

## Scoring system

Both users and validators have reputation score.

Validator who keeps bigger amount of FTT tokens at stake have bigger score. 

Validator who performed more exchanges have bigger score.

User who performed more exchanges have bigger score.

Score of the validator and the user can be downvoted by other users.

## Security of operations

First and main security measure is a stake requirement for the Validator: validator should keep some amount of FTT tokens at stake. 

In case of security breach or lost funds, upon user complain, consensus of other validators can sweep out the stake of failed validator. 

Validator earns trust by succefully executing exchanges without user complains.

Multiple validators can potentially participate in one swap (exchange operation) in order to reduce risks.

## Picking up a validator

User can set up a minimal score for picking up a validator for each swap. 

Score of particular validator for a specific order is calcualted dynamically: 
```
FactualScore = ValidatorScore * (ValidatorStake/OrderSize)
```




