
# AtomChange

## Intro
AtomChange - is an open economic model community, initially gathered around decentralized multiblockchain interaction and exchange platform.

## Values
Please read and contemplate on the core values our community is based on, before moving further:
1. Openness and full (even radical) transparency
2. Freedom to participate, to join or leave the community in any role
3. Ultimate power in the hands of the community members (token holders)
4. Efforts should bring benefit to all community members
5. Open dialog

All our activity and decisions supposed to be based on these five values.

## Building blocks
There are several elements mentioned in the definition:
1. AtomChange Blockchain - is a Delegated Proof of Stake general-purpose public decentralized blockchain.
2. Open economic model, as a way to expand and enrich ecosystem.
3. Decentralized multiblockchain interaction and exchange platform, as a first application implemented on the platform.

# AtomChange blockchain


## Motivation and preface
Our aim is to create a decentralized community platform governed by the community.
First of all, community be ultimate source of decisions regarding how platform functions.

In order to do this, community should be able to change also the rules how decisions are made in the community also.

In all existing decentralized systems, end users or community members are already in some sense decision makers in a way that they choose what platform to use, and, if no one uses the platform, it dies.

With the development of public blockchains, such events as forks came onto the scene.
Eventually, fork is an event, when some part of the community does not agrees with another part of the community and decides to go on their own way. In blockchain universe, such events can be easily handled.

We do not see forks as an issue. Diversity is pre-requirement for the freedom of choice, the basic human right.

Diversity creates problems only if there is an isolation. If there is free interaction between multiple platforms, open flow of ideas and values, diversity actually increases general well-being by offering more choice.
Therefore we are building this platform.

## Basic consensus
The version of the platform end users accessing depends on a which version signing nodes (full nodes) running.
But ultimately if the platform have too many nodes in brings a lot of issues related to speed and synchronization.

We believe that Delegated Proof of Stake system is the optimal solution, existing and tested so far today.

Delegated Proof of Stake means all tokenholders can vote and elect nodes who is in their turn, responsible for the running full nodes with proper version of the software.

In order to minimize risks of chain fork, we have to design such governance system that is highly flexible and provides maximum power directly to the end users. This is possible if there will be an instruments to change basic properties of the system on user voting event.

During the system launch, in the genesis block there will be 21 predefined nodes who will have the right to sign blocks.

Initially, for the each signed block, full node will be receiving 10 ATM tokens as a block reward.

All token holders can initiate voting to elect and assign new signing nodes, up to 108, or fire existing ones.

Consensus rules themselves implemented as a smart contract and all token holders can initiate voting for migration into new consensus contract.

## Technical properties
AtomChange blockchain is based on ethereum fork as the most convenient general-purpose smart contract platform. However, we understand that its performance is very limited. One of the main development priorities will be improving platform performance: increasing block speed and increasing transaction capacity.

# Open Economic Model

 Open Economic Model designed in order optimize issuance mechanics of public economic networks and give the ability to deploy new non-profit (general welfare) and for-profit projects on top of already existing networks.

## Problems with existing economic models
 Fiat systems:
 * Not Transparent
 * Not controllable by public
 * Capable of doing some welfare efforts (government -> taxes -> social welfare projects), but often not very effective (corruption, bureaucracy, absence competition)

Established Blockchain Networks:
 * Transparent
 * Controllable by public (community)
 * Not set up for general-welfare projects (infective mining and emission algorithms)
 * No effective incentives to develop existing network

New Blockchain Networks set up through an ICO (Token Generation Events):
* An ICO event essentially creates new separated community instead of expanding existing one
* Unreasonable funding targets (projects trying to raise much more than they need in order to reach to next milestone)
* No effective incentives to develop existing network
* Hight risks and high percentage of scam projects

## Desired properties
After analyzing the current landscape of solutions, we can form the list of desired properties for the new system:
* Effective incentives to improve existing network
* Milestone-based, iterative funding for new projects
* Full transparency
* Ultimate power in the hands of the community
* Effective way to incorporate both non-proft (general welfare) and for-profit (commercial) projects into community economy

Example use cases:
* Set up several foundations of independent groups of developers for the codebase improvements
* Build roads in the city
* Finance community-owned commercial enterprise
* Build hospital for the community
* Implement new project that is fully tied to the root tokens with new utility and the market, for example, Golem project, instead of issuing new token could tie its functionality directly to Ether.

## Emission model
If we take analogy to the known things, emission of new tokens is essentially equal to the all community members paying taxes.

Burning tokens (destroying existing ones) is similar to paying dividends to all existing token holders. When you extract some amount of tokens from the open market, this act will increase economic value of the remaining tokens.

Community have the ultimate power and emission (funding) events happen according to tokenholders voting. We call it `community funding contract`. In fact, `community funding contract` is not a direct issuing event, but it is a 'license' for the managers of the project to issue certain amount of tokens.

`Community funding contracts` can vary in properties.

Amount limits for the `community funding contract` can be:
* Specified in ATM tokens
* Specified in stable value equivalent, we use labour-hour rate as a most stable value (implemented through the pricefeed published by signing nodes)

In most cases there is no need to issue large amount of tokens at once. Most of the projects require regular ongoing funding. Therefore `community funding contract` can have multiple timeframe based limits - daily, monthly, yearly, lifetime, etc. Examples:
* 100 000 tokens total
* 100 labour-hour per month during the next 12 months
* 500 labour-hour per month, without end time specified (until community will revoke the contract)

Any `community funding contract` can be revoked on community voting. This is required to prevent further funding of failing projects, block compromised contracts or unscrupulous project managers.

## Board of Guardians

`Board of Guardians` is group consisting from 3 to 12 community members elected by all tokenholders. The responsibility of the board is to approve any community community voting requests. This is required to avoid low quality, scam or malicious voting proposals.
Each member of the board receives 'salary', defined by a community via board-targeted `community funding contract`.

## Voting rules
Each voting have `15 days` voting time window. Voting is considered successful with any rate of participation.

Inactive addresses who did not participate in the voting are fined with `1% inactivity tax`.  

Voters, who voted against majority are fined with `minority tax`. This is required to discourage automatic (bot) voting.  

`Minority tax` is calculated in the following way:
```
contractMaxIssuance = maximum amount of tokens can be issued by the funding contract in next 12 months
minorityTax =  contractMaxIssuance / tokensInExistance * 0.05
```

It is expected, that not everyone will be able to follow up community voting requests. To do this properly, it will take time and expertise. Therefore, voting power of an account can be delegated to another account. We call such accounts `community activists`. If `community activist` votes against majority, `minority tax` applies proportionately to all his electorate.

An additional `qualification tax` applies to the `community activist` in case of minority voting.
```
Qualification tax = minority tax collected from electorate * 0.2
```

`Community activist` is allowed to vote only if he keeps at stake amount of tokens, sufficient to pay `qualification tax` in case of minority voting.

All applicable taxes does not redistribute tokens, but only burns them.

`Community activist` can set a fee, payable by his electorate on each voting.  

## Community voting requests

###  Declaration of Values
Community have declaration of values.

Projects wishing to submit community funding request, have to comply with the declaration.

### Funding direction
Community funded projects spend funds on anything beyond stated mission.

Each issuance and spending transaction should be published and explained.

In case community is not satisfied with the level of transparency, spending directions or any other properties of the project, it can revoke `community funding contract`.

### Non-profit projects
Can be non-profit:
* Dispatches funds into non-refundable community-welfare project

Examples:
* Deploying cross-continental data cable
* Promoting token of the community and expanding community
* Building roads in the community
* Further development of the blockchain
* Building free hospital in the community

### For-profit projects
Community dividends:

Burning community tokens essentially equals to paying out dividends to all community members

If the for-profit community-funded project eventually in due course of its economic activity burns more tokens, than was issued to it, the project increases general welfare

Can have legally or technically (smart contract) defined % reward for project managers

## Implications/assumptions
No such models exists on any viable scale

DAOs based on Open Economic model can scale and grow faster than other types of DAOs

Wealth distribution will become much more smooth than with current models

Society will become more open, transparent and responsible

Open Economic Model can supply social welfare needs and deploy general well-being in much more efficient way, than existing government-tax model

Open Economic model can, and probably will replace state-centric society organization


# AtomChange Exchange Platform

## Intro

We believe blockchain ecosystem have a unavoidable need for multiblockchain interaction platforms in order to make a next step and the development of the industry.

At he moment there are tens of very advanced distributed blockchain platforms but there is no way to interact for them except through centralized platforms.

All the centralized exchanges bears full pack of respective risks and inconvenience connected with central point of attack and control.

Our goal is to make an open, easily extandable platform and standard for multiblockchain interaction. We do not want to work several years on something that will turn out impractical. We want to implement the system step by step in short milestones that would be usable by community by themselves.

## Concept

AtomChange Blockchain should be DPoS blockchain.

First of all, DPoS blockchain leaves ultimate power in the hands of community.

And second, DPoS consensus model allows to have fast enough platform due to limited amount of supporting nodes.

Each signing node is elected by token holders and receives fixed 'salary' in form of tokens set up for the supporting nodes.

Blockchain keeps:
1. ATM balance and transaction records
2. Voting records
3. Governance rules
4. Reputation scores
5. Orderbook
6. Trade history with links to transactions on other chains.
7. Other custom and user-deployed smart contracts

Please check [architecture](https://github.com/atomchange/wiki/blob/master/architecture.md) for more details on the side of implementation.

## Tools

As an initial base, [Quorum](https://github.com/atomchaneg/quorum) can be used for first proof of concept.

DPoS consensus and open economic model will be implemented as a smart contract (quorum moved consensus onto smart contract level).

For the ethereum family chains we need to implement smart contract templates for validators.

For the bitcoin family exchange should be performed with multisig wallets.

## Architecture Principles

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

## Exchange Roadmap

First and most important use case of multiblockchain interaction is a token exchange.

Considering iterative approach, the first several milestones would be:
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

There are two contracts created on AtomChange network and Ethereum network.

Each contract receives funds from sender.

As soon as each contracted credited with pre-agreed amount of tokens, Validator puts its signature and receiving side can claim newly acquired tokens

## ATM to BTC exchange

AtomChange network exchange implemented via smart contract, descibed above.
Bitcoin network exchange implemented via 2of3 multisig address on the bitcoin network with signing right from the Validator.

## BTC to ETH exchange

After both of above case are implemented, BTC to ETH exchange also becomes possible.

## Orderbook

Global Orderbook is kept in AtomChange blockchain.

Considering that AtomChange is a DPoS system, we can achieve tolerable speed for the initial phase of the project.

## Scoring system

Both users and validators have reputation score.

Validator who keeps bigger amount of ATM tokens at stake have bigger score.

Validator who performed more exchanges have bigger score.

User who performed more exchanges have bigger score.

Score of the validator and the user can be downvoted by other users.

## Security of operations

First and main security measure is a stake requirement for the Validator: validator should keep some amount of ATM tokens at stake.

In case of security breach or lost funds, upon user complain, consensus of other validators can sweep out the stake of failed validator.

Validator earns trust by successfully executing exchanges without user complains.

Multiple validators can potentially participate in one swap (exchange operation) in order to reduce risks.

## Picking up a validator

User can set up a minimal score for picking up a validator for each swap.

Score of particular validator for a specific order is calcualted dynamically:
```
FactualScore = ValidatorScore * (ValidatorStake/OrderSize)
```




## Links

Here are some other projects, moving into similar directions, where we can find some good ideas.

https://www.coindesk.com/bitcoin-meets-zcash-developers-test-tool-trustless-trades/ - can be potentially used in the future.

https://www.coindesk.com/cross-blockchain-trades-lightning-gives-new-life-atomic-swaps/ - can be potentially used in the future.

https://github.com/zcash-hackworks/zbxcat

https://nvo.io/

https://cosmos.network/

https://localbitcoins.com/

https://twitter.com/decredproject/status/910224860625780736

https://github.com/decred/dcps/blob/master/dcp-0002/dcp-0002.mediawiki

https://bitcoinmagazine.com/articles/atomic-swaps-how-the-lightning-network-extends-to-altcoins-1484157052/

https://github.com/decred/atomicswap/#first-mainnet-dcr-ltc-atomic-swap

https://en.bitcoin.it/wiki/Atomic_cross-chain_trading

https://themerkle.com/what-is-an-atomic-swap/

https://www.wanchain.org - really good project
