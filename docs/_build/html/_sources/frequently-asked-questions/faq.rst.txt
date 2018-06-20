################################################################################
Frequently Asked Questions
################################################################################

.. contents::
  :local:
  :depth: 2

Questions
================================================================================

Who is in control of Bitcoin?
--------------------------------------------------------------------------------

Nobody owns the Bitcoin network much like no one owns the technology behind email. Bitcoin is controlled by all Bitcoin users around the world. While developers are improving the software, they can't force a change in the Bitcoin protocol because all users are free to choose what software and version they use. In order to stay compatible with each other, all users need to use software complying with the same rules. Bitcoin can only work correctly with a complete consensus among all users. Therefore, all users and developers have a strong incentive to protect this consensus.

Source: https://bitcoin.org/en/faq#who-controls-the-bitcoin-network

How does one acquire bitcoins?
--------------------------------------------------------------------------------

* As payment for goods or services.
* Purchase bitcoins at a Bitcoin exchange.
* Exchange bitcoins with someone near you.
* Earn bitcoins through competitive mining.

While it may be possible to find individuals who wish to sell bitcoins in exchange for a credit card or PayPal payment, most exchanges do not allow funding via these payment methods. This is due to cases where someone buys bitcoins with PayPal, and then reverses their half of the transaction. This is commonly referred to as a chargeback.

Source: https://bitcoin.org/en/faq#how-does-one-acquire-bitcoins

What does "synchronizing" mean and why does it take so long?
--------------------------------------------------------------------------------

Long synchronization time is only required with full node clients like Bitcoin Core. Technically speaking, synchronizing is the process of downloading and verifying all previous Bitcoin transactions on the network. For some Bitcoin clients to calculate the spendable balance of your Bitcoin wallet and make new transactions, it needs to be aware of all previous transactions. This step can be resource intensive and requires sufficient bandwidth and storage to accommodate the full size of the block chain. For Bitcoin to remain secure, enough people should keep using full node clients because they perform the task of validating and relaying transactions.

Source: https://support.bitxoxo.com/hc/en-us/articles/208411029-What-does-synchronizing-mean-and-why-does-it-take-so-long-

What is a consensus algorithm and why is it useful in blockchain?
--------------------------------------------------------------------------------

A consensus algorithm is a process in computer science used to achieve agreement on a single data value among distributed processes or systems. Consensus algorithms are designed to achieve reliability in a network involving multiple unreliable nodes. Solving that issue -- known as the consensus problem -- is important in distributed computing and multi-agent systems.


To accommodate this reality, consensus algorithms necessarily assume that some processes and systems will be unavailable and that some communications will be lost. As a result, consensus algorithms must be fault-tolerant. They typically assume, for example, that only a portion of nodes will respond but require a response from that portion, such as 51%, at a minimum.

Applications of consensus algorithms include:

Deciding whether to commit a distributed transaction to a database.
Designating node as a leader for some distributed task.
Synchronizing state machine replicas and ensuring consistency among them.
Consensus algorithms support many real-world systems including Google's PageRank, load balancing, smart grids, clock synchronization and drone control.

Blockchain, the distributed ledger most commonly associated with Bitcoin, also relies on consensus algorithms to reach agreement among nodes. A blockchain can be thought of as a decentralized database that is managed by distributed computers on a peer-to-peer (P2P) network. Each peer maintains a copy of the ledger to prevent a single point of failure (SPOF). Updates and validations are reflected in all copies simultaneously.

Bitcoin uses the proof of work algorithm (PoW) to ensure security in a trustless network, by including mechanisms that ensure that the effort of mining is represented within the block submitted by the miner. Software on the computers of miners accesses their processing capacity to solve transaction-related algorithms. The block is an encrypted hash proof of work that is created in a compute-intensive process. Although any party can submit a chain of blocks to the ledger, the amount of computing resources required to fake consensus is too great to make it worthwhile to a dishonest party.

Other common consensus algorithms include the practical Byzantine fault tolerance algorithm (PBFT), the proof-of-stake algorithm (PoS) and the delegated proof-of-stake algorithm (DPoS).

Source: https://whatis.techtarget.com/definition/consensus-algorithm

What is the difference between a public and private/consortium blockchains?
--------------------------------------------------------------------------------

* **Public blockchains**: a public blockchain is a blockchain that anyone in the world can read, anyone in the world can send transactions to and expect to see them included if they are valid, and anyone in the world can participate in the consensus process – the process for determining what blocks get added to the chain and what the current state is. As a substitute for centralized or quasi-centralized trust, public blockchains are secured by cryptoeconomics – the combination of economic   incentives and cryptographic verification using mechanisms such as proof of work or proof of stake, following a general principle that the degree to which someone can have an influence in the consensus process is proportional to the quantity of economic resources that they can bring to bear. These blockchains are generally considered to be “fully decentralized”.
* **Consortium blockchains**: a consortium blockchain is a blockchain where the consensus process is controlled by a pre-selected set of nodes; for example, one might imagine a consortium of 15 financial institutions, each of which operates a node and of which 10 must sign every block in order for the block to be valid. The right to read the blockchain may be public, or restricted to the participants, and there are also hybrid routes such as the root hashes of the blocks being public together with an API that allows members of the public to make a limited number of queries and get back cryptographic proofs of some parts of the blockchain state. These blockchains may be considered “partially decentralized”.
* **Fully private blockchains**: a fully private blockchain is a blockchain where write permissions are kept centralized to one organization. Read permissions may be public or restricted to an arbitrary extent. Likely applications include database management, auditing, etc internal to a single company, and so public readability may not be necessary in many cases at all, though in other cases public auditability is desired.

Source: https://blog.ethereum.org/2015/08/07/on-public-and-private-blockchains/

If the Bitcoin's database is on my computer, can I add 1000 of BTC in my wallet?
--------------------------------------------------------------------------------

The blockchain is famous for its security: once the data is there it is impossible to modify it.

The blockchain consists of a chain of blocks, where every block contains data (for instance a money transactions, documents or personal data).
When a new block is to be added to the chain, it has to be verified by the network of nodes first, and once this is done, the transaction can be inserted in the blockchain. There are mining and a consensus protocol standing behind this phase (click here to read more).
The blocks are connected with each other in a way that if I edit the content of one block I must edit all the following blocks, moreover to edit a block you need the consensus of other nodes.
Hence the more people are using a blockchain, the longer it is and the more secure the system is.

Source: http://www.ledgerprojects.com/blockchain-for-dummies/

Why do I have to wait for confirmation?
--------------------------------------------------------------------------------

Receiving notification of a payment is almost instant with Bitcoin. However, there is a delay before the network begins to confirm your transaction by including it in a block. A confirmation means that there is a consensus on the network that the bitcoins you received haven't been sent to anyone else and are considered your property. Once your transaction has been included in one block, it will continue to be buried under every block after it, which will exponentially consolidate this consensus and decrease the risk of a reversed transaction. Each confirmation takes between a few seconds and 90 minutes, with 10 minutes being the average. If the transaction pays too low a fee or is otherwise atypical, getting the first confirmation can take much longer. Every user is free to determine at what point they consider a transaction sufficiently confirmed, but 6 confirmations is often considered to be as safe as waiting 6 months on a credit card transaction.

Source: https://bitcoin.org/en/faq#why-do-i-have-to-wait-10-minutes

How much will the transaction fee be?
--------------------------------------------------------------------------------

Transactions can be processed without fees, but trying to send free transactions can require waiting days or weeks. Although fees may increase over time, normal fees currently only cost a tiny amount. By default, all Bitcoin wallets listed on Bitcoin.org add what they think is an appropriate fee to your transactions; most of those wallets will also give you chance to review the fee before sending the transaction.

Transaction fees are used as a protection against users sending transactions to overload the network and as a way to pay miners for their work helping to secure the network. The precise manner in which fees work is still being developed and will change over time. Because the fee is not related to the amount of bitcoins being sent, it may seem extremely low or unfairly high. Instead, the fee is relative to the number of bytes in the transaction, so using multisig or spending multiple previously-received amounts may cost more than simpler transactions. If your activity follows the pattern of conventional transactions, you won't have to pay unusually high fees.

Source: https://bitcoin.org/en/faq#how-much-will-the-transaction-fee-be

What if I receive a bitcoin when my computer is powered off?
--------------------------------------------------------------------------------

This works fine. The bitcoins will appear next time you start your wallet application. Bitcoins are not actually received by the software on your computer, they are appended to a public ledger that is shared between all the devices on the network. If you are sent bitcoins when your wallet client program is not running and you later launch it, it will download blocks and catch up with any transactions it did not already know about, and the bitcoins will eventually appear as if they were just received in real time. Your wallet is only needed when you wish to spend bitcoins.

Source: https://bitcoin.org/en/faq#what-if-i-receive-a-bitcoin-when-my-computer-is-powered-off

How does mining help secure Bitcoin?
--------------------------------------------------------------------------------

Mining creates the equivalent of a competitive lottery that makes it very difficult for anyone to consecutively add new blocks of transactions into the block chain. This protects the neutrality of the network by preventing any individual from gaining the power to block certain transactions. This also prevents any individual from replacing parts of the block chain to roll back their own spends, which could be used to defraud other users. Mining makes it exponentially more difficult to reverse a past transaction by requiring the rewriting of all blocks following this transaction.

Source: https://bitcoin.org/en/faq#how-does-mining-help-secure-bitcoin

What do I need to start mining?
--------------------------------------------------------------------------------

In the early days of Bitcoin, anyone could find a new block using their computer's CPU. As more and more people started mining, the difficulty of finding new blocks increased greatly to the point where the only cost-effective method of mining today is using specialized hardware. You can visit BitcoinMining.com for more information.

Source: https://bitcoin.org/en/faq#what-do-i-need-to-start-mining

Hasn't Bitcoin been hacked in the past?
--------------------------------------------------------------------------------

The rules of the protocol and the cryptography used for Bitcoin are still working years after its inception, which is a good indication that the concept is well designed. However, security flaws have been found and fixed over time in various software implementations. Like any other form of software, the security of Bitcoin software depends on the speed with which problems are found and fixed. The more such issues are discovered, the more Bitcoin is gaining maturity.

There are often misconceptions about thefts and security breaches that happened on diverse exchanges and businesses. Although these events are unfortunate, none of them involve Bitcoin itself being hacked, nor imply inherent flaws in Bitcoin; just like a bank robbery doesn't mean that the dollar is compromised. However, it is accurate to say that a complete set of good practices and intuitive security solutions is needed to give users better protection of their money, and to reduce the general risk of theft and loss. Over the course of the last few years, such security features have quickly developed, such as wallet encryption, offline wallets, hardware wallets, and multi-signature transactions.

Source: https://bitcoin.org/en/faq#hasnt-bitcoin-been-hacked-in-the-past
