********************************************************************************
Glossary
********************************************************************************
.. glossary::
   :sorted:

   Altcoins
    Altcoin is an abbreviation of “Bitcoin alternative”. Currently, the majority of altcoins are forks of Bitcoin with usually minor changes to the proof of work (POW) algorithm of the Bitcoin blockchain. The most prominent altcoin is Litecoin. Litecoin introduces changes to the original Bitcoin protocol such as decreased block generation time, increased maximum number of coins and different hashing algorithm

   ASIC
    An “Application Specific Integrated Circuit” is a silicon chip specifically designed to do a single task. In the case of Bitcoin, they are designed to process SHA-256 hashing problems to mine new bitcoins. ASICs are considered to be much more efficient than conventional hardware(CPUs, GPUs). Using a regular computer for Bitcoin mining is seen as unprofitable and only results in higher electricity bill

   Bitcoin
    is a cryptocurrency that runs on a (1) global peer to peer network, is (2) decentralised (no single entity can control it), it’s (3) open source (wallet & transaction verification), (4) bypassing middlemen or central authority, with (5) no issuer or acquirer, (6) anyone with a computer or smartphone can use it

   Bitcoin ATM
    A cash point where people can trade fiat currency and bitcoins

   Blockchain
    Shared, trusted, public ledger of transactions, that everyone can inspect but which no single user controls. It is a cryptographed, secure, tamper-resistant distributed database. It solves a complex mathematical problem to exist. A blockchain is a perfect place to store value, identities, agreements, property rights, credentials, etc. Once you put something like a Bitcoin into it, it will stay there forever. It is decentralized, disintermediated, cheap and censorship-resistant. Applications of Blockchain: Bitcoin (cryptocurrency), Namecoin (wants to replace the entire DNS system of the Internet), or Sia (a decentralized cloud storage), Ethereum (Turing complete Virtual Machine where you can run any smart contract); Any centralized service like eBay, Dropbox can potentially be built in a decentralized way using blockchain technology, considerably lowering transaction costs

   Block explorer
    An online tool for exploring the blockchain of a particular cryptocurrency, where you can watch and follow live all the transactions happening on the blockchain. Block explorers can serve as blockchain analysis and provide information such as total network hash rate, coin supply, transaction growth, etc.

   Block reward
    An amount of crypto-currency a miner receives for processing transactions in a given block. Because creating (or “mining”) blocks is so crucial to the security of the Bitcoin network and yet so hard, the Bitcoin protocol includes a mechanism to encourage people to mine: every time a block is added, the miner who found the block is given 12,5 BTC(this number will change at the next halving in 2020) as a block reward

   Chain linking
    Chain linking is the process of connecting two blockchains with each other, thus allowing transactions between the chains to take place. This will allow blockchains like Bitcoin to communicate with other sidechains, allowing the exchange of assets between them

   Client
    A software program a user executes on a desktop, laptop or a mobile device to launch an application

   Cloud Mining
    Classical cryptocurrency mining requires huge investments in hardware and electricity. Cloud mining companies aim to make mining accessible to everybody. People just can log in to a website and invest money in the company which already has mining datacenters. The money is managed by the company and it is invested in mining equipment. Investors get a share of the revenue. The disadvantage for the user is that cloud mining has low returns compared to traditional mining.

   Consensus (general)
    A fundamental problem in distributed computing is to achieve overall system reliability in the presence of a number of faulty processes. This often requires processes to agree on some data value that is needed during computation. The consensus problem requires agreement among a number of processes for a single data value. Some of the processes may fail or be unreliable in other ways, so consensus protocols must be fault tolerant. The processes must somehow put forth their candidate values, communicate with one another, and agree on a single consensus value. The bitcoin blockchain uses electricity to ensure the security of the system. It creates an economic system where you can only participate by incurring costs, Proof of work (POW). You do that for the possibility of reward/bitcoin. If you spend money, and you play fair by the rules, you get money back. If you cheat, you lose money. It doesn’t pay to cheat. This simple game theoretical equilibrium is the core of the bitcoin consensus algorithm

   Consensus (Bitcoin’s Process Consensus)
    Developers suggest bitcoin improvements/modifications, small or big, proposals on Github, Bitcointalk, Reddit, mailing lists, etc. Discussion on this level is critical to enable smooth runtime consensus transitions.Modifications with reference implementations get tested on the testnet. After successful testing developers implement the changes into the Bitcoin software. Who has a say in the consensus process?: (1) Software Developers (do the reference implementations), (2) Miners (Runtime consensus for mining blocks), (3) Exchanges (They run nodes that validate transactions), (4) Wallet companies (create transactions run on nodes), (5) Merchants (Merchant processing also through nodes)

   Consortium blockchains
    A consortium blockchain is a blockchain where the consensus process is controlled by a pre-selected set of nodes; for example, one might imagine a consortium of 15 financial institutions, each of which operates a node and of which ten must sign every block for the block to be valid. The right to read the blockchain may be public or restricted to the participants. There are also hybrid routes such as the root hashes of the blocks being public together with an API that allows members of the public to make a limited number of queries and get back cryptographic proofs of some parts of the blockchain state. These blockchains may be considered “partially decentralized”

   Cryptographic Hash Function
    The cryptographic hash function is a mathematical algorithm that takes a particular input which can be any kind of digital data be it a password or jpeg file and produces a single fixed length output. Some examples of different hash function algorithms are MD5, MD4 or SHA256. The last one is used in the Bitcoin protocol. Main properties: (1) easy to compute hash value for any given message (2) infeasible to generate a message from its hash except by trying all possible input combinations(brute force attack) (3) infeasible to modify a message without changing the hash (4) infeasible to find two different messages with the same hash (5) deterministic so the same message always results in the same hash. Cryptographic hash functions have many information security applications, notably in digital signatures, message authentication codes (MACs), and other forms of authentication. They can also be used as ordinary hash functions, to index data in hash tables, for fingerprinting, to detect duplicate data or uniquely identify files, and as checksums to detect accidental data corruption

   Cryptojacking
    Cryptojacking is referred as a secret use of a device to mine cryptocurrency. The first widely known attempt for cryptojacking was the torrent tracker Piratebay. They enabled an in-browser mining software so when somebody visits the website his/her computer will start mining cryptocurrency via the browser. Users started noticing the unusual behavior in their browsers and Piratebay took down the software. There have been many attempts for cryptojacking since then. The easiest way to find out if a computer is mining cryptocurrency is to check the resources monitor for unusual CPU behavior or using the debug console of your browser an look for mining scripts. Developers also released Chrome browser extensions to protect users from mining occurring on their devices.

   Digital Signature
    Private keys are used for signing transactions. Each time a transaction is sent over the blockchain it gets signed by the user’s private key. The signed transaction is broadcasted over the network together with the corresponding public key. Each miner is able to verify the signature by verifying the signature with the public key.

   Double Spending
    Double-spending is the result of successfully spending some money more than once. Bitcoin is the first to implemented a solution in early 2009 which protects against double spending by verifying each transaction added to the blockchain to ensure that the inputs for the transaction had not previously already been spent

   Fiat currency
    Any money declared by a government to be to be valid for meeting a financial obligation, like USD or EUR

   Fork
    The creation of an ongoing alternative version of the blockchain, by creating two blocks simultaneously on different parts of the network. This creates two parallel blockchains, where one of the two is the winning blockchain. The winning blockchain gets determined by its users, by the majority choosing on which blockchain their clients should be listening

   Genesis block
    The very first block in the blockchain

   Hardfork
    A hardfork is a change to the blockchain protocol that makes previously invalid blocks/transactions valid, and therefore requires all users to upgrade their clients. The most recent example of a hardfork in public blockchains is the Ethereum hardfork which happened on July 21st, 2016. The hardfork changed the Ethereum protocol, therefore a second blockchain emerged (Ethereum Classic, ETC) which supports the old Ethereum protocol. In order to continue existing ETC needs miners, which would validate the transactions on the blockchain

   Hashcash
    is a proof-of-work system used to limit email spam and denial-of-service attacks, and more recently has become known for its use in bitcoin (and other cryptocurrencies) as part of the mining algorithm. Hashcash was proposed in May 1997 by Adam Back

   Halving
    A reduction in the block reward given to crypto-currency miners once a certain number of blocks have been mined. The Bitcoin block mining reward halves every 210,000 blocks

   Initial Coin Offering (ICO)
    ICOs are types of crowdfunding mechanisms conducted on the blockchain. Originally, the main idea of an ICO was to fund new projects by pre-selling coins/tokens to investors interested in the project. Entrepreneurs present a whitepaper describing the business model and the technical specifications of a project before the ICO. They lay out a timeline for the project and set a target budget where they describe the future funds spending (marketing, R&D, etc.) as well as coin distribution (how many coins are they going to keep for themselves, token supply, etc.). During the crowdfunding campaign, investors purchase tokens with already established cryptocurrencies like Bitcoin and Ethereum.

   IPFS
    The InterPlanetary File System (IPFS) is a hypermedia distribution protocol, addressed by content and identities. IPFS enables the creation of completely distributed applications. It aims to make the web faster, safer, and more open. IPFS is an open source project developed by the team at Interplanetary Networks and many contributors from the open source community. It is a peer-to-peer distributed file system that seeks to connect all computing devices with the same system of files. In some ways, IPFS is similar to the Web, but IPFS could be seen as a single BitTorrent swarm, exchanging objects within one Git repository. In other words, IPFS provides a high throughput content-addressed block storage model, with content-addressed hyperlinks. This forms a generalized Merkle DAG, a data structure upon which one can build versioned file systems, blockchains, and even a Permanent Web. IPFS combines a distributed hash table, an incentivized block exchange, and a self-certifying namespace. IPFS has no single point of failure, and nodes do not need to trust each other

   Light Node
    A computer on a blockchain network that only verifies a limited number of transactions relevant to its dealings, making use of the simplified payment verification (SPV) mode

   Lightning Network
    The Lightning network is a decentralized network using smart contract functionality on the blockchain to enable instant payments across a network of participants. The Lightning Network will allow bitcoin transactions to happen instantly, without worrying about block confirmation times. It will allow millions of transactions in a few seconds, at low costs, even between different blockchains, as long as both chains use the same cryptographic hash function. The Lightning network will allow two participants on the network to create a ledger entry, conduct a number of transactions between themselves and after the process has finished, record the state of the transactions on the blockchain. As for now, the bitcoin network is capable of processing up to 7 transactions per second. The Visa payment network, for instance, is believed to complete 45,000 transactions per second during a regular holiday period. This protocol tries to solve the bitcoin scalability problem

   Merkle tree
    The basic idea behind Merkle tree is to have some piece of data that is linking to another. You can do this by linking things together with a cryptographic hash. The content itself can be used to determine the hash. By using the cryptographic hashing we can address the content, and content gets immutable because if you change anything in the data, the cryptographic hash changes and the link will be different. Bitcoin uses cryptographic hashing, where every block points to the previous one if you modify the block, the hash will change and will make the block invalid

   Mining (Bitcoin)
    Mining is the process of adding transaction records to Bitcoin’s public ledger of past transactions or blockchain. This ledger of past transactions is called the blockchain as it is a chain of blocks. The blockchain serves to confirm transactions to the rest of the network as having taken place. Bitcoin nodes use the blockchain to distinguish legitimate Bitcoin transactions from attempts to re-spend coins that have already been spent elsewhere. Mining is intentionally designed to be resource-intensive and challenging so that the number of blocks found each day by miners remains steady. Individual blocks must contain a proof of work to be considered valid. This proof of work is verified by other Bitcoin nodes each time they receive a block. Bitcoin uses the hashcash proof-of-work function. The primary purpose of mining is to allow Bitcoin nodes to reach a secure, tamper-resistant consensus. Mining is also the mechanism used to introduce Bitcoins into the system: Miners are paid any transaction fees as well as a “subsidy” of newly created coins. This both serves the purpose of disseminating new coins in a decentralized manner as well as motivating people to provide security for the system

   Mining Difficulty
    Mining difficulty measures how hard it would be to find the next Bitcoin block. Every proof of work consensus algorithm has a mining difficulty which is also adjustable. Depending on how many miners join the network the difficulty might rise or fall. The aim of the difficulty is to keep the block times even and make the network secure. The average time for finding a Bitcoin block is set for 10 minutes. Litecoin is set for 2.5 minutes.

   Mining Pool
    In a mining pool, different users organize together in order to provide computing power for the bitcoin network. If a Bitcoin block is newly created, each of the users in the mining pool receives its fair share proportionately to his mining power. To become a member of a mining pool, the user needs to run software provided by the mining pool. The advantage of the mining pools is that block rewards get distributed across the pool providing more stable income.

   Node (Full Node)
    Any computer that connects to the blockchain network is called a node. Nodes that fully enforce all of the rules of the blockchain (i.e., Bitcoin) are called full nodes. Most nodes on the network are lightweight nodes instead of full nodes, but full nodes form the backbone of the network

   Oracles
    Smart contracts on the blockchain cannot access the outside network on their own. Therefore oracles sit between a smart contract and the external world, providing the data needed by the smart contract to prove performance while sending its commands to external systems

   Private Blockchains
    a fully private blockchain is a blockchain where write permissions are kept centralized to one organization. Read permissions may be public or restricted to an arbitrary extent. Likely applications include database management, auditing, etc. internal to a single company, and so public readability may not be necessary in many cases at all, though in other cases public auditability is desired

   Private key
    Each time a user runs a cryptocurrency wallet for the first time a public-private key pair gets generated. The private key is a randomly generated number which allows users to transact over the blockchain. It is locally stored and kept secret. Each time a Bitcoin gets sent a private key has to sign the transaction. This action is automatically executed by the wallet software. When a wallet asks users to do a backup what this means is that the users must secure their private key. There are different types of wallets such as online wallets, mobile wallets, desktop wallet, hardware wallets or paper wallets. The category of each wallet is determined by where private keys are stored. Online wallets are mostly provided by exchanges and keep user’s private keys on their servers. If the service provider goes offline users would lose access to their funds. Hardware wallets for example store user’s private keys in a secure device which looks like a USB flash drive.

   Proof of Authority(PoA)
    A Proof of authority is a consensus mechanism in a private blockchain which essentially gives one client(or a specific number of clients) with one particular private key the right to make all of the blocks in the blockchain

   Proof of Stake
    Proof-of-stake (PoS) is a method by which a cryptocurrency blockchain network aims to achieve distributed consensus. While the proof-of-work (PoW) method asks users to repeatedly run hashing algorithms or other client puzzles, to validate electronic transactions, proof-of-stake asks users to prove ownership of a certain amount of currency (their “stake” in the currency). Peercoin was the first cryptocurrency to launch using proof-of-Stake. Other prominent implementations are found in BitShares, Nxt, BlackCoin, NuShares/NuBits and Qora. Ethereum has planned a hard fork transition from PoW to PoS consensus. Decred hybridizes PoW with PoS and combines elements of both in an attempt to garner the benefits of the two systems and create a more robust notion of consensus. With Proof of Work, the probability of mining a block depends on the work done by the miner (e.g. CPU/GPU cycles spent checking hashes). In the case of Bitcoin, with Proof of Stake, the resource that’s compared is the amount of Bitcoin a miner holds – someone holding 1% of the Bitcoin can mine 1% of the “Proof of Stake blocks”. Instead of sacrificing energy to mine a block, a user must prove they own a certain amount of the cryptocurrency to generate a block. The more stake you own, the more likely you are to generate a block. In theory, this should prevent users from creating forks because it will devalue their stake and it should save a lot of energy. Proof of Stake sounds like a good idea, but ironically, there is the “Nothing at Stake” problem. Since mining Bitcoins is costly, it is not smart to waste your energy on a fork that won’t earn you any money, however with Proof of Stake, it is free to mine a fork

   Proof of Work
    POW system/protocol/function is an economic measure to deter denial of service attacks and other service abuses such as spam on a network by requiring some work from the service requester, usually meaning processing time by a computer. The concept may have been first presented by Cynthia Dwork and Moni Naor in a 1993 journal. The term “Proof of Work” was first coined and formalized in a 1999 paper by Markus Jakobsson and Ari Juels. A key feature of these schemes is their asymmetry: the work must be moderately hard (but feasible) on the requester side but easy to check for the service provider. This idea is also known as a CPU cost function, client puzzle, computational puzzle or CPU pricing function

   Public Blockchains
    a public blockchain is a blockchain that anyone in the world can read, anyone in the world can send transactions to and expect to see them included if they are valid, and anyone in the world can participate in the consensus process – the process for determining what blocks get added to the chain and what the current state is. As a substitute for centralized or quasi-centralized trust, public blockchains are secured by crypto economics – the combination of economic incentives and cryptographic verification using mechanisms such as proof of work or proof of stake, following a general principle that the degree to which someone can have an influence in the consensus process is proportional to the quantity of economic resources that they can bring to bear. These blockchains are generally considered to be “fully decentralized”

   Ring Signature
    Ring signature is a cryptographic technology that could provide a decent level of anonymisation on a blockchain. Ring signatures make sure individual transaction outputs on the blockchain can’t be traced. A message signed with a ring signature is endorsed by someone in a particular group of people. One of the security properties of a ring signature is that it should be computationally infeasible to determine which of the group members’ keys was used to produce the signature

   Satoshi
    The smallest unit of Bitcoin, equal to 0.00000001 BTC

   Satoshi Nakamoto
    is a person or group of people who created the bitcoin protocol and reference software, Bitcoin Core (formerly known as Bitcoin-Qt). In 2008, Nakamoto published a paper on The Cryptography Mailing list at metzdowd.com describing the bitcoin digital currency. In 2009, they released the first bitcoin software that launched the network and the first units of the bitcoin cryptocurrency, called bitcoins

   SHA (Secure Hash Algorithm)
    is a family of cryptographic hash functions published by the National Institute of Standards and Technology (NIST) as a U.S. Federal Information Processing Standard (FIPS). SHA256 is an algorithm used in Bitcoin that takes an input of any size which can be any form of data(text, jpeg, pdf, etc.), mixes it up and creates a fixed size output(a hash) which is 256-bit (32-byte) long . You can think of the hash as the fingerprint of the data. Hashes are one-way functions – they cannot be decrypted back. The only way to decrypt a hash is by brute forcing it. Brute force means to systematically try all the combinations for an input. Brute force attack will always find the input, no matter its complexity. The downside is whether or not you will still be alive when it finally guesses it

   Sidechains
    are blockchains that are interoperable with each other and with Bitcoin, avoiding liquidity shortages, market fluctuations, fragmentation, security breaches and outright fraud associated with alternative crypto-currencies. “Sidechains are new blockchains which are backed by Bitcoins, via Bitcoin contracts, just as dollars and pounds used to be backed by cold hard gold. You could in principle have thousands of sidechains “pegged” to Bitcoin, all with different characteristics and purposes … and all of them taking advantage of the scarcity and resilience guaranteed by the main Bitcoin blockchain, which in turn could iterate to implement experimental sidechain features once they have been tried and tested…” more

   Softfork
    A softfork is a change to the bitcoin protocol wherein only previously valid blocks/transactions are made invalid. Since old nodes will recognize the new blocks as valid, a softfork is backward-compatible. This kind of fork requires only a majority of the miners upgrading to enforce the new rules

   SPV(Simplified Payment Verification) client
    SPV clients are Bitcoin lightweight clients which do not download and store the whole blockchain locally. These wallets provide a way to verify payments without having to download the complete blockchain. An SPV client only downloads the block headers by connecting to a full node

   State Channel
    State channels are interactions which get conducted off the blockchain without significantly increasing the risk of any participant. Moving these interactions off of the chain without requiring any additional trust can lead to significant improvements in cost and speed. State channels work by locking part of the blockchain state so that a specific set of participants must completely agree with each other to update it

   Token
    In the context of Blockchains, a token is a digital identity for something that can be owned. Historically, tokens started as meta information encoded in simple Bitcoin transactions, thereby taking advantage of the Bitcoin blockchain’s strong immutability. At a protocol layer, tokens were outsourced extensions to Bitcoin’s core protocol. Instead of being integrated as a feature on a software level, those tokens were created by misappropriating data fields in Bitcoin transactions (such as encoding data in the amount or op_return field). Today, modern tokens are created as sophisticated smart contract systems with complex permission systems and interaction paths attached. Smart contracts can be understood as software agents, which act deterministically and autonomously, within the scope of a given network, according to a predefined rule set. If the governance rules around issuance and management of a token are sufficiently complex regarding how they coordinate a group of stakeholders, token smart contracts may be understood as organizations sui generis. The management rules may reflect those of known legal, organizational entities such as stock corporations, but they do not have to

   Testnet
    a second blockchain used by developers for testing new versions of client software without putting a real value at risk

   Transaction Fees (Bitcoin)
    may be included with any transfer of bitcoins from one address to another. At the moment, many transactions are typically processed in a way where no fee is expected at all, but for transactions which draw coins from many bitcoin addresses and therefore have a large data size, a small transaction fee is usually expected. The transaction fee is processed by and received by the bitcoin miner. When a new bitcoin block is generated with a successful hash, the information for all of the transactions is included with the block, and all transaction fees are collected by that user creating the block, who is free to assign those fees to himself. Transaction fees are voluntary on the part of the person making the bitcoin transaction, as the person attempting to make a transaction can include any fee or none at all in the transaction. On the other hand, nobody mining new bitcoins necessarily needs to accept the transactions and include them in the new block being created. The transaction fee is, therefore, an incentive on the part of the bitcoin user to make sure that a particular transaction will get included in the next block which is generated. It is envisioned that over time the cumulative effect of collecting transaction fees will allow somebody creating new blocks to “earn” more bitcoins that will be mined from new bitcoins created by the new block itself. This is also an incentive to keep trying to create new blocks even if the value of the newly created block from the mining activity is zero in the far future

   Turing completeness
    A machine is Turing complete if it can perform any calculation that any other programmable computer is capable of. All modern computers are Turing-complete in this sense. The Ethereum Virtual Machine (EVM) which runs on the Ethereum blockchain is Turing complete. Thus it can process any “computable function”. It is, in short, able to do what you could do with any conventional computer and programming language

   Wallet
    is a file that contains a collection of private keys and communicates with the corresponding blockchain. Wallets contain keys, not coins. Wallets require backups for security reasons.

   Whisper
    Whisper is a part of the Ethereum p2p protocol suite that allows for messaging between users via the same network that the blockchain runs on. The main task of whisper will be the provision of a communication protocol between dapps

   51% attack
    A condition in which more than half the computing power of a cryptocurrency network is controlled by a single malicious miner or group of miners. If he controls 51% of the network that makes him the authority on the network, giving him the power to spend the same coins multiple times, issue transactions that conflict with someone else’s or stop someone else’s transaction from being confirmed

Source: https://blockchainhub.net/blockchain-glossary/
