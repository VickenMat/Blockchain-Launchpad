# Launchpad

## Blockchain

A [blockchain](https://www.reuters.com/graphics/TECHNOLOGY-BLOCKCHAIN/010070P11GN/index.html) is a decentralized, distributed, and immutable database, or ledger, that maintains a continuously growing list of records and transactions across a network of computers.

At a [high level](https://mitsloan.mit.edu/ideas-made-to-matter/blockchain-explained), blockchains allow a network of computers to agree at regular intervals on the true state of a distributed ledger. These ledgers can contain any type of data such as currency, digital rights, intellectual property, and identity or property titles. The ledger is secured through cryptography and game theory, and does not require trusted nodes like traditional networks. 

### Characteristics

- [Distributed](https://www.investopedia.com/terms/d/distributed-ledger-technology-dlt.asp) - 
All network participants have access to the ledger and its record of transactions. Transactions are recorded once and shared across the network
- [Immutable](https://www.ledger.com/academy/glossary/immutable) - No participant is able to change or tamper with a transaction after it has been recorded in the ledger. If a transaction includes an error, a new transaction must be added to reverse it
- [Decentralized](https://www.lcx.com/what-is-decentralization-in-blockchain/) - Control over the network (authority and decision-making) is equally distributed amongst all participant, elmininating the need for a central authority(individual or organizaton). This distribution of control enhances transparency and fairness while making it resistent to censorship and external manipulation

### How it works

When [transactions](https://ethereum.org/en/developers/docs/transactions/) on a network occur, they are chronologically stored in digital structures called [blocks](https://ethereum.org/en/developers/docs/blocks/) and cryptographically chained together through linking the block's unique [hash](https://www.scalingparrots.com/en/blockchain-hash-what-is-it/) (digital fingerprint) with the previous one. This chain of blocks is shared across the network and copies exist and are simultaneosly updated with every fully participating [node](https://ethereum.org/en/developers/docs/nodes-and-clients/) in the ecosystem. Each block stores the previous block's hash, timestamp, transaction data, and nonce. For the majority of networks, processing a transaction involves recording an [account](https://ethereum.org/en/developers/docs/accounts/) via asymmetric key pairs and the corresponding coin or token balances. A consensus mechanism, which will be unique to each network, is utilized to verify and finalize the trade. Layer-1 blockchains feature their own native tokens which are used to pay [gas fees](https://ethereum.org/en/developers/docs/gas/).

![image](https://github.com/VickenMat/Blockchain-Launchpad/assets/113546737/d2a0dfed-d0a3-4348-81e5-2c5a1ce532e2)

### Consensus Mechanisms

Traditional financial institutions rely on central authorities to protect their data and keep systems runnings. To achieve consensus in a decentralized system, protocols and incentives are put in place enabling a network of nodes to agree on transactions and the state of the blockchain, creating a governance approach that keeps it secure and functional. This allows all parties agree on the definition of network-verified transactions. [Consensus mechanisms](https://ethereum.org/en/developers/docs/consensus-mechanisms/) are the foundation of many cryptocurrencies, yet there are multiple approaches.

#### [Proof of Work](https://ethereum.org/en/developers/docs/consensus-mechanisms/pow/)

#### [Proof of Stake](https://ethereum.org/en/developers/docs/consensus-mechanisms/pos/)

#### [Proof of Authority](https://ethereum.org/en/developers/docs/consensus-mechanisms/poa/)

#### [Proof of Capacity](https://www.geeksforgeeks.org/proof-of-capacity/)

#### [Proof of Activity](https://www.linkedin.com/pulse/proof-activity-blockchain-hybrid-consensus-mechanism-part-bansal/)

#### [Proof of Importance](https://www.geeksforgeeks.org/proof-of-importance-poi-in-blockchain/)

#### [Proof of History](https://www.scalingparrots.com/en/proof-of-history-what-is-it/)

#### [Proof of Burn](https://www.geeksforgeeks.org/proof-of-burn-consensus-algorithm-in-blockchain/)

#### [Proof of Time Elapsed](https://medium.com/unicorn-ultra/what-is-proof-of-elapsed-time-poet-unlocking-the-secrets-of-proof-of-elapsed-time-poet-0bb7dd1b614e)

Useful articles - [Making Sense of Bitcoin and the Blockchain](https://www.pwc.com/us/en/industries/financial-services/fintech/bitcoin-blockchain-cryptocurrency.html), [Blockchain Facts](https://www.investopedia.com/terms/b/blockchain.asp), [What is a Blockchain](https://www.ibm.com/topics/what-is-blockchain), and [Understanding Blockchain Technology](https://builtin.com/blockchain)

Useful videos - [Blockchain Tutorial](https://www.simplilearn.com/tutorials/blockchain-tutorial), [Foundations of Blockchain](https://www.youtube.com/playlist?list=PLEGCF-WLh2RLOHv_xUGLqRts_9JxrckiA), and [Blockchain & Money](https://youtu.be/EH6vE97qIP4)

If you're looking for project ideas, visit [Blockchain Projects w/ Source Code - InterviewBit](https://www.interviewbit.com/blog/blockchain-projects/)

## Layer 1

A cryptocurrency is a digital medium of exchange, created and stored on the blockchain using cryptography to verify the transfer of funds and creation of monetary units. They do not have any intrinsic value, no physical form, and suppy is determined by the protocol

[Layer 1](https://www.lcx.com/layer-1-blockchain-explained/) refers to the most fundamental blockchain protocol that serves as the network's foundation. It is essential a distributed ledger designed to securely record transactions on a public, immutable, and trustless ledger. They are the foundation because it provides the infrastructure for all applications and protocols developed on top of the network. It's primary responsibilities are maintaining the distributed ledger, validating transactions, and protecting the network from threats. All on-chain transactions are executed on layer-1 and therefore serves as the source of truth. 

### Bitcoin

#### [Bitcoin Whitepaper](https://bitcoin.org/bitcoin.pdf)

#### [Bitcoin Mining - Investopedia](https://www.investopedia.com/tech/how-does-bitcoin-mining-work/)

#### [Bitcoin Halving - Investopedia](https://www.investopedia.com/bitcoin-halving-4843769)

#### [Proof of Work]()

### Ethereum

#### [Ethereum Whitepaper](https://ethereum.org/en/whitepaper/)

#### [Intro to Ethereum - Ethereum](https://ethereum.org/en/developers/docs/intro-to-ethereum/)

#### [Intro to Ether - Ethereum](https://ethereum.org/en/developers/docs/intro-to-ether/)

#### [Networks - Ethereum](https://ethereum.org/en/developers/docs/networks/)

#### [What is Ethereum - Investopedia](https://www.investopedia.com/terms/e/ethereum.asp)

### [BTC/ETH Game Theory - Medium](https://medium.com/@TrustlessState/ethereum-the-money-game-landscape-1b9fdb05f842)

### Token Standards

#### [ERC-20 - Ethereum](https://ethereum.org/en/developers/docs/standards/tokens/erc-20/)

#### [ERC-721 - Ethereum](https://ethereum.org/en/developers/docs/standards/tokens/erc-721/)

#### [ERC-1155 - Ethereum](https://ethereum.org/en/developers/docs/standards/tokens/erc-1155/)


## Layer 2

### Scaling a Blockchain

#### [Scaling - Ethereum](https://ethereum.org/en/developers/docs/scaling/)

#### [Optimistic Rollups - Ethereum](https://ethereum.org/en/developers/docs/scaling/optimistic-rollups/)

#### [Zero Knowledge Rollups - Ethereum](https://ethereum.org/en/developers/docs/scaling/zk-rollups/)

#### [State Channels - Ethereum](https://ethereum.org/en/developers/docs/scaling/state-channels/)

#### [Sidechains - Ethereum](https://ethereum.org/en/developers/docs/scaling/sidechains)

#### [Plasma - Ethereum](https://ethereum.org/en/developers/docs/scaling/plasma)

#### [Validium - Ethereum](https://ethereum.org/en/developers/docs/scaling/validium/)

### Oracles

#### [Oracles - Ethereum](https://ethereum.org/en/developers/docs/oracles/)

### Chainlink

### [Chainlink and Blockchain - Hackernoon](https://hackernoon.com/is-chainlink-the-one-ring-to-rule-them-all-lf163283)

#### [Chainlink Use Cases](https://blog.chain.link/smart-contract-use-cases/)


## Stablecoins

#### [What are Stablecoins - Investopedia](https://www.investopedia.com/terms/s/stablecoin.asp#:~:text=Stablecoins%20are%20cryptocurrencies%20that%20attempt,a%20commodity%20such%20as%20gold)


## Smart Contracts

#### [Smart Contracts - Ethereum](https://ethereum.org/en/developers/docs/smart-contracts/)

#### [What are Smart Contracts - IBM](https://www.ibm.com/topics/smart-contracts)

#### [Smart Contracts Explained - BitDegree](https://www.bitdegree.org/crypto/tutorials/what-is-a-smart-contract)

#### [Intro to Smart Contracts and their Limitations - Harvard Law](https://corpgov.law.harvard.edu/2018/05/26/an-introduction-to-smart-contracts-and-their-potential-and-inherent-limitations/)

## Use Cases

Blockchains have the capacity to disrupt any industry, some being central banks, finance, money transfer, micropayments, identity, privacy, IoT, robotics, artificial intelligence, ownership and many more

### dApps

#### [Intro to dApps - Ethereum](https://ethereum.org/en/developers/docs/dapps/)

#### [dApps - Investopedia](https://www.investopedia.com/terms/d/decentralized-applications-dapps.asp)

#### [dApps Explained w/ Examples - Hackernoon](https://hackernoon.com/what-are-decentralized-applications-dapps-explained-with-examples-7ff8f2c4a460)


### De-Fi

#### [DeFi - Investopedia](https://www.investopedia.com/decentralized-finance-defi-5113835)

#### [DeFi Projects - DeFi Prime](https://defiprime.com/)

#### [DeFi Tutorial](https://fastdefitutorial.com/)


## Web 3.0

#### [Web 2 v Web 3 - Ethereum](https://ethereum.org/en/developers/docs/web2-vs-web3/)

#### [Web3 - Coinmarketcap](https://coinmarketcap.com/alexandria/article/what-is-web-3-0)

#### [What is Web3 - NYTimes](https://www.nytimes.com/interactive/2022/03/18/technology/web3-definition-internet.html)

## Storage

#### [Hot v Cold Storage - InvestorJunkie](https://investorjunkie.com/crypto/hot-wallet-vs-cold-wallet/)

## Blockchain Trilemma

### Decentralization


## Books


