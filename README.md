# gitcoin-network-security-hackathon submission: 
# 4 Ideas for Security

## Progress:

### Idea #1 - Chop Up, Spread Out

Chop up and spread out transactions among nodes (like coinjoin/mixers), internet communications among p2p nodes (like lbry/Tor), funds storage among UTXOs (like Bitcoin/offline wallet generation), and this strategy can be applied to not only blockchain transactions but any transactions of a sensitive nature.

### Idea #2 - Alternatives to Key Exchange

Transition from a server-based internet with TLS exchange-based communications to a meshnet with content-based addressing or other alternatives to exchanging keys.

### Idea #3 - Surveillors are Surveillable

Make not only requester and receiver IP addresses viewable in metadata (for internet communications), but also make tamperer/intercepter activity/identity viewable using quantum cryptography or other alternatives.

### Idea #4 - Protect Nodes from Being Targeted

Whether using PoW or PoS, reward nodes (miners or validators) for being online rather than slashing them for being offline (possibly unintentionally, see PoS stake-grinding vulnerability in https://arxiv.org/abs/1904.04098). Instead just skip over offline nodes. Also we need to protect block proposers from being targeted for attack. 

### Note Regarding Selfish Mining

1. The selfish mining attack problem in PoW is equivalent to the Byzantine attack problem in PoS.
2. Both only work if the malicious group comprises between 33% and 50% of nodes AND has communication controlling/withholding ability (https://arxiv.org/abs/1904.04098). 
3. Both are solved by the fact that malicious groups are susceptible to being attacked by other malicious groups (see my paper at https://ipfs.io/ipfs/QmPtaLUMFiMU8EUSjQs5TbqJaSpM6xBoDBVVH1Maxdo13C?filename=SELF_CUSTODIAL_WALLET_REVISED.PDF). 

### Findings from Attending MyData2020

Details: https://online2020.mydata.org/

* Countries (EU, Japan) are responding to increasing pressure to sell citizens' data.

* The flow of data/data controls between companies is akin to the flow of people/passports between countries.

* **All solutions ultimately boil down to trust.**

  - A way to "see" morality of people, organizations, etc.

  - Users play a role

  - Data regulations and processes apply to data regulators and processors
  
  - Is achieved by transparency and controls

* Data transfer requires money transfer ...

![Woodblock puzzle](https://thumbs.dreamstime.com/z/wooden-puzzle-isolated-16214441.jpg)

## Demos:

IPFS demo (https://youtu.be/EV8qCLYuNm8)

## Value Proposition:

Any amount of security is currently still built on infrastructure called the Internet, which we are giving a much-needed security upgrade.

## Technical Development:

We are merging teams with [RaidGuild](https://raidguild.org/).

