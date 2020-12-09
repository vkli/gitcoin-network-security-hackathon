# gitcoin-network-security-hackathon submission

## 4 Ideas for Security:

1. Chop up and spread out transactions among nodes (like coinjoin/mixers), internet communications among p2p nodes (like lbry/Tor), funds storage among UTXOs (like Bitcoin/offline wallet generation), and this strategy can be applied to anything of a sensitive nature.
2. Transition from a server-based internet with TLS exchange-based communications to a meshnet with content-based addressing or other alternatives to exchanging keys.
3. Make not only requester and receiver IP addresses viewable in metadata (for internet communications), but also make tamperer/intercepter activity/identity viewable using quantum cryptography or other alternatives.
4. Whether using PoW or PoS, reward nodes (miners or validators) for being online rather than slashing them for being offline (possibly unintentionally, see PoS stake-grinding vulnerability in https://arxiv.org/abs/1904.04098, instead just skip over offline nodes, also need to protect block proposers from being targeted for attack). 

\* Note Regarding Selfish Mining:

1. The selfish mining attack problem in PoW is equivalent to the Byzantine attack problem in PoS.
2. Both only work if the malicious group comprises between 33% and 50% of nodes AND has communication controlling/withholding ability (https://arxiv.org/abs/1904.04098). 
3. Both are solved by the fact that malicious groups are susceptible to being attacked by other malicious groups (see my paper at https://ipfs.io/ipfs/QmPtaLUMFiMU8EUSjQs5TbqJaSpM6xBoDBVVH1Maxdo13C?filename=SELF_CUSTODIAL_WALLET_REVISED.PDF). 

## Demos:

IPFS demo (https://youtu.be/EV8qCLYuNm8)

## Value Proposition:

Any amount of security at the upper level is still built on infrastructure called the Internet, which we are giving a much-needed security upgrade.

## Technical Development:

We are merging teams with [RaidGuild](https://raidguild.org/).
