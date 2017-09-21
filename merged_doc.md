
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
But ultimately if the platform have too many nodes in brings a lot of issues related to speed and syncronization.

We belive that Delegated Proof of Stake system is the optimal solution, existing and tested today.

Delegated Proof of Stake means all tokenholders can vote and elect nodes who is in their turn, responsible for the running full nodes with proper version of the software.

## 1. System Launch
Initial 21 full node runners download the software and join the network. They get 10 tokens per mined block.

# Open Economic Model

## Empowering You
Community members have real power

1 token = 1 vote power

Delegated Proof of Stake Consensus

Community elects number of delegates, who in turn runs efficient decentralized network

Delegates can be added/revoked by a community at any time

Delegates receives decent fixed salary (newly issued coins) set by a community

Community can change the rules

Community can change consensus model

And… Community can issue new tokens

Stop. What?

## Problems with existing solutions
Old System:
* Not Transparent, not controllable by public
* Still doing some welfare efforts (government -> taxes -> social welfare projects)

Existing Blockchain Networks
* Transparent
* Controllable by public
* Not set up for general-welfare projects

## What if?
I want to do some project, that will benefit all token holders (community)?
* Develop new opensource wallet for the community?
* Build roads in the community?

How do I get money?

## Compaing Ways of funding
ICO/Separate funding campaign -> effectively creates new community

Emission (essentially equals to taxes) -> all community members pay

## Decision making, simple
Project submits proposal

Community votes

Project gets funded

All community members (token holders get deluded little bit)

## Decision making, advanced
What if community grows too big?

Decision making process is not efficient

Too many scam projects will be submitted

Low voting participation

Low average qualification of the community

## Guardian Boards
Community can elect Guardian Boards

Guardian Boards can be multi-level or segmented by expertise

Project submits proposal

Guardian Board approves/bans project (filtering bad ones)

Community votes on approved project

Project gets funded

## Community Activists
Voting power of an account can be trusted to another one

Active voting can be stimulated with small rewards

Missed voting can be punished with small tax, thus stimulating token holders either actively vote or delegate their voting power

Community Activists subgroup emerges out of the community (more qualified community members who regularly vote on projects, pursuing general well-being)

Community Activists can share part of voting reward to voting power owner

## Declaration of Values
Community have declaration of values

Projects have to comply with the declaration

Open and transparent: projects should have completely transparent and public operations

Neutral and do-good: should not discriminate members of community and should bring benefit for all community members

Have ‘Community Project’ legal properties

## Legal properties
Cannot spend received funds on anything beyond stated mission

Should be legally or technically (smart contract) obliged to utilize funds in way stated to community during voting

Managers can define their compensation before putting the project on voting

## Non-profit projects
Can be non-profit:
* Dispatches funds into non-refundable community-welfare project

Examples:
* Deploying cross-continental data cable
* Promoting token of the community and expanding community
* Building roads in the community
* Further development of the blockchain
* Building free hospital in the community

## For-profit projects
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

# AtomChange Blockchain

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

DPoS consesus and open economic model will be implemented as a smart contract (quorum moved consesus onto smart contract level).

For the ethereum family chains we need to implement smart contract templates for validators.

For the bitcoin family exchange should be performed with multisig wallets.

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

Validator earns trust by succefully executing exchanges without user complains.

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
