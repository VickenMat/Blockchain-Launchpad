# Launchpad

## Blockchain

A [blockchain](https://www.reuters.com/graphics/TECHNOLOGY-BLOCKCHAIN/010070P11GN/index.html) is a decentralized, distributed, and immutable database, or ledger, that maintains a continuously growing list of records and transactions across a network of computers.

At a [high level](https://mitsloan.mit.edu/ideas-made-to-matter/blockchain-explained), blockchains allow a network of computers to agree at regular intervals on the true state of a distributed ledger. These ledgers can contain any type of data such as currency, digital rights, intellectual property, and identity or property titles. The ledger is secured through cryptography and game theory, and does not require trusted nodes like traditional networks. 

![image](https://media.geeksforgeeks.org/wp-content/uploads/20221111160733/Structureofblocksinblockchain.png)

### Characteristics

- [Decentralized](https://www.lcx.com/what-is-decentralization-in-blockchain/) - Control over the network (authority and decision-making) is equally distributed amongst all participant, elmininating the need for a central authority(individual or organizaton). This distribution of control enhances transparency and fairness while making it resistent to censorship and external manipulation
- [Distributed](https://www.investopedia.com/terms/d/distributed-ledger-technology-dlt.asp) - 
All network participants have access to the ledger and its record of transactions. Transactions are recorded once and shared across the network
- [Immutable](https://www.ledger.com/academy/glossary/immutable) - No participant is able to change or tamper with a transaction after it has been recorded in the ledger. If a transaction includes an error, a new transaction must be added to reverse it

![image](https://miro.medium.com/v2/resize:fit:4800/format:webp/1*UDQuCant9h02OfmPVc0zqw.png)

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

Useful articles - [Making Sense of Bitcoin and the Blockchain](https://www.pwc.com/us/en/industries/financial-services/fintech/bitcoin-blockchain-cryptocurrency.html), [Blockchain Facts](https://www.investopedia.com/terms/b/blockchain.asp), [What is a Blockchain](https://www.ibm.com/topics/what-is-blockchain), [Understanding Blockchain Technology](https://builtin.com/blockchain), and [Bitcoin Explained](https://www.lopp.net/bitcoin-information/bitcoin-explained.html)

Useful videos - [Blockchain Tutorial](https://www.simplilearn.com/tutorials/blockchain-tutorial), [Foundations of Blockchain](https://www.youtube.com/playlist?list=PLEGCF-WLh2RLOHv_xUGLqRts_9JxrckiA), and [Blockchain & Money](https://youtu.be/EH6vE97qIP4)

If you're looking for project ideas, visit [Blockchain Projects w/ Source Code - InterviewBit](https://www.interviewbit.com/blog/blockchain-projects/)

***

## Cryptocurrencies

A cryptocurrency is a digital, encrypted, and decentralized medium of exchange that runs on the blockchain. Unlike the U.S. dollar, there is no central authority like the government that manages or maintains the value of it. Instead, these tasks are disributed among the nodes via the Internet. To use a cryptocurrency, you need a wallet, which is a cloud based-service stored on your device intended to store your encryption keys that confirm your identity and link to your crypto.

### [Benefits](https://www.grantthornton.com/insights/capabilities/advisory/blockchain-101-for-business-the-benefits-and-risks)

- Lower fees : Cheaper to transfer money than going through centralized banks, especially compared to global wire transfers
- Faster times : Receive and send crypto withing minutes as opposed to the 24-48 hour (not including weekends) transfer time
- Transparency : The blockchain is fully public and immutable, meaning it cannot be manipulated or deleted. Every transaction can be seen or tracked at any time
- Fraud Detection : A shared blockchain can be used to detect fraud, even when entities are not at liberty to share all the of the identifying details
- International Trade : As opposed to maneuving through a complex network of negotiations spanning suppliers, manufacturers, distributors, retailers, and countries, blockchains allow you to bypass them and transact with low fees and quick transfers
- Independence : Cryptocurrencies are designed to be decentralized without the control of a single government or central bank. Users have unrestricted access to their coins, but this also means full responsibility
- Accessibility : Users do not need access to traditional banking and its resitrictions to use or purchase tokens. All that is required is an internet connection and a wallet address

### [Risks](https://www.fidelity.com/learning-center/trading-investing/crypto/risks-and-benefits-of-crypto)

- Regulatory Uncertainties : Government regulations around the world are constantly evolving and differ from country to country. Regulations may impact how you use or access your crypto, which leads to price volatility. It will take time for policymakers to establish clear and consistent guidelines as the blockchain space is still new
- Data Processing Demands : Many blockchains use Proof of Work consensus model, which requires nodes to independently validate transactions through the use of physical compute power
- Volatility : The values for crypto tokens shift more than typical investments
- Securities and Scams : Some exchanges and Web3 platforms are more secure than others and newer coins could be at a higher scam risk than mor eestablished ones. There is no protection loss or insurance for lost or stolen cryptocurrency
- Storage : The two primary ways to store your crypto are on non-custodial wallets on personal devices(hot wallet) or using a third party cold storage wallet. Due to the nature of blockchains, you are soley responsible for the safety and security of your crypto. If you lose your private keys or a virus corrupts your wallet, you may lose your funds.

## Blockchain Layers

![image](https://github.com/VickenMat/Blockchain-Launchpad/assets/113546737/51435efc-bec3-4472-ad9d-c8076661cf20)


## Layer-0

[Layer-0](https://www.lcx.com/layers-of-blockchain-explained/) refers to the blockchain itself and provides the fundamental infrastructure, standards, and protocols that govern the network. It is the initial stage of the blockchain that enables Layer-1s to function and includes the Internet, hardware, and a variety of other connections.

## Layer-1

A cryptocurrency is a digital medium of exchange, created and stored on the blockchain using cryptography to verify the transfer of funds and creation of monetary units. They do not have any intrinsic value, no physical form, and suppy is determined by the protocol

[Layer-1](https://www.lcx.com/layer-1-blockchain-explained/) blockchain refers to the protocol that serves as a [network's](https://ethereum.org/en/developers/docs/networks/) foundation. It is a distributed ledger designed to securely record transactions on a public, immutable, and trustless database. They are the foundation because it provides the infrastructure for all applications and protocols developed on top of the network. It's primary responsibilities are maintaining the distributed ledger, validating transactions, and protecting the network from threats. All on-chain transactions are executed on layer-1s and therefore serves as the source of truth. 

Key Features

- Consensus Mechanism : Layer-1s employ various consensus mechanisms to validate transactions and achieve agreement between all nodes in a network as seen above
- Security : Utilize cryptographic algorithms (hashing) and decentralized network structures to ensure the immmutability of a blockchain 
- Scalability : Many blockchains face the issue of scalability as they need to accomodate for a large amount of users
- Smart Contracts : Various blockchains such as Ethereum support the execution of smart contracts, which are self-executing contracts with the terms of agreement directly written in the code

### [Bitcoin](https://bitcoin.org/en/) (BTC)

![image](https://www.investopedia.com/thmb/dERboL3dYS7NCsTY5NgB6b8thIQ=/750x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/dotdash_Final_Blockchain_Sep_2020-01-60f31a638c4944abbcfde92e1a408a30.jpg)

Bitcoin, is a peer-to-peer cryptocurrency, meaning that all transactions happen between equal, independent network participants without the need for intermediaries. Bitcoin was created to allow "online payments to be sent directly from one part to another without going through a financial institution" and is designed for value transfer. It is the the first and most well-known blockchain and utilizes the Proof of Work (PoW) consensus mechanism. Bitcoin employs various techniques that are now common such as [mining](https://www.investopedia.com/tech/how-does-bitcoin-mining-work/) and the [Bitcoin Halving](https://www.investopedia.com/bitcoin-halving-4843769).

#### [Bitcoin Whitepaper](https://bitcoin.org/bitcoin.pdf)

### [Ethereum](https://ethereum.org/en/) (ETH)

Ethereum is an open-source blockchain renowned for its ability to create smart contracts and be a platform for decentralized applications. It introduced the idea of programmable money, revolutionizing the blockchain landscape. It employs a Proof of Work (PoW) consensus mechanism , although it is transitioning to Proof of Stake (PoS) in Ethereum 2.0. Additional information on Ethereum can be found at [Intro to Ethereum](https://ethereum.org/en/developers/docs/intro-to-ethereum/) and [Intro to Ether](https://ethereum.org/en/developers/docs/intro-to-ether/)

#### [Ethereum Whitepaper](https://ethereum.org/en/whitepaper/)

#### [BTC/ETH Game Theory](https://medium.com/@TrustlessState/ethereum-the-money-game-landscape-1b9fdb05f842)

#### Ethereum Token Standards

[Token standards](https://crypto.com/university/what-are-token-standards) are a set of rules that run crypto tokens on a blockchain. ERC, or Ethereum Request for Comment is a set of technical documents containing guidelines on developing a smart contract. The most common token standard is [ERC-20](https://ethereum.org/en/developers/docs/standards/tokens/erc-20/), which is a blueprint for creating fungible tokens on the Ethereum network. In contast, the primary non-fungible token standards are [ERC-721](https://ethereum.org/en/developers/docs/standards/tokens/erc-721/) and [ERC-1155](https://ethereum.org/en/developers/docs/standards/tokens/erc-1155/).

### [Polkadot](https://polkadot.network/) (DOT)

Polkadot is an open-source sharded multichain protocol that focuses on interoperability between different Layer-1 blockchains. It enables the seamless transfer of assets and data across multiple chains while utilizing a unique shared responsibility model and the Nominated Proof of Stake (NPoS) consensus mechanism.

### [Solana](https://solana.com/) (SOL)

Solana aims to resolve the scalability issues of L1 blockchains by employing a Proof of History consensus to achieve TPS of up to 65,000. It is an open-source project capitalizing on the blockchain's permissionless strcuture to provide decentralized finance (DeFi) solutions.

### [Avalance](https://www.avax.network/) (AVAX)

Avalanche is a platform utliziing Proof of Stake (PoS) for DApps and custom blockchain networks. It aims to support a TPS of 6,500 without compromising scalability through the use of its unique tri-chain structure, the X-Chain (Exchange), C-Chain (Contract), and P-Chain (Platform). Each chain has its distinct purpose and all nodes validate all transactions, which is radically different than the approach Bitcoin and Ethereum use. 

### [Binance](https://www.binance.com/en) (BNB)

Binance aims to bring cryptocurrency exchanges to the forefront of financial global activity. Aside from being the largest crypto exchange in the world, Binance has a whole ecosystem of functionalities such as the Binance Chain, Binance Smart Chain, Binance Academy, and Trust Wallet. Binance uses a combination of Proof of Stake (PoS) and Proof of Authority (PoA) to validate network transaction.

### [Cardano](https://cardano.org/) (ADA)

Cardano is a Proof of Stake (PoS) blockchain who's goal is to allow "changemakers, innovators, and visionaries" to bring positive global change. It is an open-source project aiming to "redistribute power from unaccountable structures to the margins to individuals" helping create a more transparent and fair society. Cardano is used for the creation of DApps and smart contracts to be developed with modularity.

## Layer-2

As blockchains such as Bitcoin and Ethereum grow in popularity, difficulties in processing transactions quickly and efficiently due to limitations in throughput lead to higher fees and longer confirmation times. Innovations such as [Layer-2](https://www.lcx.com/layers-of-blockchain-explained/)s are being developed to address these challenges, aiming to enhance the network's capacity to support a larger scale of users without compromising decentralization or security. They are compatible with third-party integrations and elimites Layer-1's restrictions.

### Blockchain Trilemma

The blockchain trilmma is a concept that refers to the trade off between three key properties of a blockchain, decentralization, scalability, and security. Achieving all three properties simultaneously is difficult, and improving one often comes at the expense of others.

- ### [Decentralization](https://www.blockchain-council.org/blockchain/what-is-decentralization-in-blockchain/)

The degree to which the network is distributed and not controlled by a single entity. Decentralization is on a spectrum rather than a simple "yes" or "no" and each network has its own degree of decentralization. Increasing decentralization can lead to slower TPS and higher resource requirements for nodes, making it harder to scale

- ### [Security](https://www.ibm.com/topics/blockchain-security)

A secure blockchain ensures the integrity and safety of the data it holds, making it difficult for malicious entities to manipulate it. A blockchain system is vulnerable to multiple attacks such as double spending, sybil, DDoS, and 51% attacks. The more participants in the network, the harder it is for these attacks to be successful. In PoW, each block is interconnected in a tamper-resistent manner and any alterations to the data would be quickly spotted by the network.

- ### [Scalability](https://ethereum.org/en/developers/docs/scaling/)

Capacity of a blockchain network to handle an increasing volume of users and transactions per second (TPS) without compromising speed or fees. On the blockchain, each transaction has “weight”, and the more data that’s added, the heavier and slower it is to move around. Imagine every time a transaction is submitted, the data had to wait in traffic for it to be validated. The more people transacting means the more the network validation process needs to happen, which creates a jam on an unscalable network. In PoW, the algorith will automatically alter the level of difficulty according the the available hash power and the network may support any number of nodes. [Scalability](https://shardeum.org/blog/what-is-blockchain-scalability/) is essential for widespread adoption and practical use of the network. and currently, Bitcoin can manage 7 TPS as opposed to Visa's 24,000. 

A variety of methods and techniques called Layer-2s have been employed in an effort to increase blockchain scalability such as [Optimistic Rollups](https://ethereum.org/en/developers/docs/scaling/optimistic-rollups/), [Zero Knowledge Rollups](https://ethereum.org/en/developers/docs/scaling/zk-rollups/), [State Channels](https://ethereum.org/en/developers/docs/scaling/state-channels/), [Sidechains](https://ethereum.org/en/developers/docs/scaling/sidechains), [Plasma](https://ethereum.org/en/developers/docs/scaling/plasma), and [Validium](https://ethereum.org/en/developers/docs/scaling/validium/)

### [Polygon](https://polygon.technology/) (MATIC)



### [Arbitrum](https://arbitrum.io/) (ARB)



### [Immutable X](https://www.immutable.com/) (IMX)



### [Optimism](https://www.optimism.io/) (OP)



### [zkSync](https://zksync.io/) (ZK)



## Layer-3

[Layer-3](https://www.lcx.com/layers-of-blockchain-explained/) is known as the application layer whos primary responsibility is to host DApps and numerous other protocols that facilitate other apps. It is further divided into two sub-layers, application and execution.

## Oracles

[Oracles](https://ethereum.org/en/developers/docs/oracles/) are applications that source, verify, and transmit off-chain data to smart contracts running on the blockchain. They provide a way for Web3 ecosystems to access existing data sources, legacy systems, and advanced computations, extending the utility and value of DApps. 

For example, let’s assume Alice and Bob want to bet on the outcome of a sports match. Alice bets $20 on team A and Bob bets $20 on team B, with the $40 total held in escrow by a smart contract. When the game ends, how does the smart contract know whether to release the funds to Alice or Bob? The answer is it requires an oracle mechanism to fetch accurate match outcomes offchain and deliver it to the blockchain in a secure and reliable manner.

![Problem](https://cdn.prod.website-files.com/5f75fe1dce99248be5a892db/65672cc162d319d711995419_wGf9Q3OEnxQINTT9nDXdMTM6VxwH2N0sp0OlreIrn5mhiB5HO_ElhUpOGMIfhaoyF-On930br6VyWhNHsEl999YxMwBO1I7PmEDoDeaQnGw-Hf1nvAWzso8XJW-OUjG3M1LVijtz9HPkXIDLkoRp94Q.jpeg)
By default, Ethereum based smart contracts cannot access information stored outside the blockchain network

![image](https://cdn.prod.website-files.com/5f75fe1dce99248be5a892db/65672cc1d35b5ee20cdfd250_k5eK0BYEazoyssAp_SjmzvQ30GAPnyH6cCf8zvrKQGPkfp36HjYg-EP21x_H8EqKHLZC8Vzrr477MkSaQo6Ev6drkcGZUsojPSrTZ2GUL_Ga4RQCMYFKBXaEtoyeaMipWfTWA365VeRbImjdD0Scanw.png)
Oracles act a bridge between blockchains and external systems

### [Chainlink](https://chain.link/) (LINK)

Chainlink is a decentralized blockchain [oracle](https://chain.link/education/blockchain-oracles) network built on Ethereum. It is used to facilitate the transfer of tamper-proof data from off-chain sources to on-chain smart contracts. It's [importance](https://hackernoon.com/is-chainlink-the-one-ring-to-rule-them-all-lf163283) cannot go understated as it supplies a stream of real world data to all smart contracts that need it. The [use cases](https://blog.chain.link/smart-contract-use-cases/) extend to DeFi, Chross-Chain Interoperability Protocol (CCIP), Verifiable Random Function (VRF), Proof of Reserve (PoR), Automation and much more. 

### [Pyth Network](https://pyth.network/) (PYTH)



### [API3](https://api3.org/) (API3)

 

## Stablecoins

[Stablecoins](https://www.investopedia.com/terms/s/stablecoin.asp#:~:text=Stablecoins%20are%20cryptocurrencies%20that%20attempt,a%20commodity%20such%20as%20gold) are a type of cryptocurrency that maintains a stable value by pegging their price to another currency or commodity. This makes them different than most other cryptocurrencies which are more volatile and don't have tangible assets backing them. Stablecoins can be used as a medium of exchange similar to a digital dollar becauase their value is designed to not change. There are multiple ways to maintain a stablecoin, one being backing it 1 to 1, meaning there exists 1 dollar in a vault somewhere that I can exchange it for guaranteed. The problem is that there needs to be billions of dollars waiting to be exchanged and if not there remains the risk of not being able to back it should everyone sell. The other method is called an algorithmic stablecoin. The idea is that it's backed by nothing, similar to fiat currency, but uses an cryptographic algorithm of bots who buy, sell, create, and burn tokens to keep the price constant if it rises or falls below a certain level. 

### [Tether](https://tether.to/en/) (USDT)

Tether is a stablecoin pegged to the U.S. dollar designed to allow the use of fiat currencies in a digital manner. It gives the ability to transact with traditional currencies across the blockchain, without the inherent volatility and complexity associated with a cryptocurrency. USDT does not have its own blockchain but instead operates as a second layeron top of Layer-1s such as Bitcoin or Ethereum.

### [USDC](https://www.circle.com/en/usdc) (USDC)

USDC is stablecoin backed by the U.S. dollar at a 1:1 ratio. Every unit of this crypto in circulation equates to $1 that is held in reserve, a mix of cash and short term U.S. Treasury Bonds. It provides a safe haven for traders in times of volatility and allows businesses to accept digital asset payments without the fear of price fluctuation.

### [DAI](https://makerdao.com/en/) (DAI)

Dai is an Ethereum based stablecoin whose issuance and governance is managed by the Maker Protocol and the MakerDAO decentralized autonomous organization (DAO). It's price is soft-pegged to the U.S. dollar and is collateralized by a mix of other cryptocurrencies that are deposited into smart contract vaults every time DAI is minted.

## Interoperability

[Interoperability](https://www.coinbase.com/learn/crypto-glossary/what-is-blockchain-interoperability) refers to the ability of different blockchain networks to communicate and exchange data with each other. It is crucial for the growth and development of the technology as it allows for seamless interaction to and from all blockchains, enabling the exchange of data and assets without the need for intermediaries. Interoperability is necessary for adoption, scale, and innovation.

![image](https://cdn.prod.website-files.com/5f75fe1dce99248be5a892db/643e9cb5d755e681e1c4c2e0_Cross-Chain-Smart-Contracts_2-V1.webp)

### [Cosmos](https://cosmos.network/) (ATOM)

### [Quant](https://quant.network/) (QNT)

### [Axelar](https://axelar.network/)  (AXL)

### [Darwinia Network](https://darwinia.network/) (RING)

## Decentralized Finance (DeFi)

[Decentralized Finance](https://www.coinbase.com/learn/crypto-basics/what-is-defi) is the term for peer-to-peer financial services on public blockchains. This includes earning interest, borrowing, lending, buying insurance, trade derivatives and assets, etc. The primary benefit of DeFi versus traditional financial systems is that its faster and cheaper because it doesn't require paperwork and third-parties. DeFi takes the basic idea of Bitcoin, digital money, and expands on it by creating and entire digital financial ecosystem without buildings or physical assets.

There are many DeFi [projects](https://defiprime.com/) used by millions of people today, and you can learn how to interact with them using this [tutorial](https://fastdefitutorial.com/)

### Decentralized Exchanges (DEX)

![image](https://changelly.com/blog/wp-content/uploads/2020/07/dex-1-770x425.png.webp)

A [decentralized exchange](https://chain.link/education-hub/what-is-decentralized-exchange-dex) is a peer-to-peer marketplace that enable users to trade crypto assets through blockchain transactions without the need for a custodian of centralized authority. Smart contracts facilitate the exchange of the assets and DEXs are the cornerstone of DeFi which allows more sophisticated financial products to be built on top of it.

- ### [Uniswap](https://uniswap.org/) (UNI)

- ### [Pancakeswap](https://pancakeswap.finance/) (CAKE)

- ### [Trader Joe](https://traderjoexyz.com/avalanche) (JOE)

- ### [Jupiter](https://station.jup.ag/) (JUP)

- ### [Sundaeswap](https://sundae.fi/) (SUNDAE)

- ### [Sushiswap](https://www.sushi.com/swap) (SUSHI)


### Lending

[Lending protocols](https://www.theblock.co/learn/245710/what-are-decentralized-lending-protocols) are an application of DeFi in which users can lend and borrow funds directly from each other, bypassing the need for a centralized authoritiy. Users retain full control of their assets at all times through smart contacts which allow for a transparent, immutable, and automated system for lending and borrowing. 

- ### [Aave](https://aave.com/) (AAVE)

- ### [Compound](https://compound.finance/governance/comp) (COMP)

- ### [Curve](https://curve.fi/#/ethereum/swap) (CRV)

- ### [Aerodome](https://aerodrome.finance/) (AERO)


## Decentralized Physical Infrastructure Networks (DePIN)

- ### [Internet Computer](https://internetcomputer.org/) (ICP)

- ### [Render](https://rendernetwork.com/) (RNDR)

- ### [Filecoin](https://filecoin.io/) (FIL)

- ### [Helium](https://www.helium.com/) (HNT)

- ### [Ocean Protocol](https://oceanprotocol.com/) (OCEAN)

- ### [Crust Network](https://crust.network/) (CRUST)

- ### [Marlin](https://www.marlin.org/) (POND)

- ### [Node AI](https://nodes.ai/) (GPU)

## Entertainment

### Gaming

- ### [Vulcan Forged](https://vulcanforged.com/) (PYR)

- ### [Verasity](https://www.verasity.io/?c=US) (VRA)

- ### [Illuvium](https://illuvium.io/) (ILV)

- ### [Gala](https://gala.com/) (GALA)

- ### [Beam](https://onbeam.com/) (BEAM)

- ### [KARRAT](https://www.karratcoin.com/) (KARRAT)

- ### [Gods Unchained](https://godsunchained.com/) (GODS)

- ### [Star Atlas](https://staratlas.com/) (ATLAS)

- ### [Enjin](https://enjin.io/) (ENj)

- ### [Mines of Dalarnia](https://www.minesofdalarnia.com/) (DAR)

- ### [zkRace](https://www.zkrace.com/) (ZERC)

### Gambling

- ### [Ridotto](https://ridotto.io/) (RDT)

### Non-Fungable Tokens (NFT)

- ### [Altura](https://www.alturanft.com/) (ALU)

- ### [Phantasma](https://phantasma.info/) (SOUL)

- ### [Torum](https://www.intro.torum.com/?utm_source=cmc) (XMT)

### Social-Fi

- ### [Fusionist](https://ace.fusionist.io/) (ACE)

## Artificial Intelligence (AI)

- ### [Trias](https://www.trias.one/) (Trias)

- ### [Fetch.ai](https://fetch.ai/) (FET)

- ### [PAAL AI](https://www.paal.ai/) (PAAL)

- ### [0x0.ai](https://0x0.ai/) (0x0)

- ### [Covalent](https://www.covalenthq.com/) (CQT)

- ### [ChainGPT](https://www.chaingpt.org/) (CGPT)


## Real World Assets (RWA)

- ### [Ondo](https://ondo.foundation/) (ONDO)

- ### [Reserve Rights](https://reserve.org/) (RSR)

- ### [Propy](https://propy.com/home/) (PRO)

- ### [Brillion](https://www.brillion.finance/) (DUA)

## Privacy

- ### [Monero](https://www.getmonero.org/) (XMR)

***

## Smart Contracts

![image](https://originstamp.com/blog/what-is-ethereum-and-what-are-its-use-cases/smart-contracts.png)

[Smart contracts](https://ethereum.org/en/developers/docs/smart-contracts/) are self-executing digital contracts stored on the blockchain in the form of computer code. The [transactions](https://www.bitdegree.org/crypto/tutorials/what-is-a-smart-contract) that happen in a smart contract are processed by the blockchain, and therefore can be sent automatically without a third party. They are immutable and transparent, and execute when when predetermined terms and conditions are met. Smart contracts are used to automate the execution of an agreement so that all participants can be immediately certain of the outcome. Smart contracts are the base of DApps and can be used for a multitude of purposes such as supply chain transparency, trade finance, and food supply. All Layer-2 protocols run on smart contracts.

#### [Intro to Smart Contracts and their Limitations - Harvard Law](https://corpgov.law.harvard.edu/2018/05/26/an-introduction-to-smart-contracts-and-their-potential-and-inherent-limitations/)

***

## Use Cases

Blockchains have the capacity to disrupt any industry, some being central banks, finance, money transfer, micropayments, identity, privacy, IoT, robotics, artificial intelligence, ownership and many more

### DApps

#### [Intro to DApps - Ethereum](https://ethereum.org/en/developers/docs/dapps/)

#### [DApps - Investopedia](https://www.investopedia.com/terms/d/decentralized-applications-dapps.asp)

#### [DApps Explained w/ Examples - Hackernoon](https://hackernoon.com/what-are-decentralized-applications-dapps-explained-with-examples-7ff8f2c4a460)


## Web 3.0

#### [Web 2 v Web 3 - Ethereum](https://ethereum.org/en/developers/docs/web2-vs-web3/)

#### [Web3 - Coinmarketcap](https://coinmarketcap.com/alexandria/article/what-is-web-3-0)

#### [What is Web3 - NYTimes](https://www.nytimes.com/interactive/2022/03/18/technology/web3-definition-internet.html)

***

## Storage

#### [Hot v Cold Storage - InvestorJunkie](https://investorjunkie.com/crypto/hot-wallet-vs-cold-wallet/)


## Books



