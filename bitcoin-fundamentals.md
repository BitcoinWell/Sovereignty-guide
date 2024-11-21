# Bitcoin fundamentals

## What is Bitcoin?

Bitcoin is a decentralized digital currency that enables peer-to-peer transactions without intermediaries like banks or governments. It was introduced in 2008 by the pseudonymous Satoshi Nakamoto and went live in January 2009.

At its core, Bitcoin combines cryptography, game theory incentives, and computer science to create an entirely new form of money—one that is borderless, censorship-resistant, and natively digital. It's often called "digital gold" due to its fixed supply and store-of-value properties.

## How Bitcoin works

Bitcoin operates on a decentralized network of computers (nodes) that collaboratively maintain a public ledger of all transactions, called the blockchain. When you send bitcoin, you broadcast a transaction to the network which gets bundled alongside many other transactions into a block by miners.

Miners compete to validate transactions and find a specific number (nonce) that, when combined with the block data, produces a hash meeting the current difficulty target. This proof-of-work process secures the network. When a miner finds a valid nonce, their block is added to the blockchain and they are rewarded with newly minted bitcoin.

This decentralized, cryptographically-secured process is what enables Bitcoin to function without any central authority or single point of control. The rules of the network, like the fixed supply of 21 million BTC, are enforced by consensus among participants.

Quick tip: You might notice we spell bitcoin with a capital B and other times with a lowercase b. The difference is if we are referring to Bitcoin the network, or bitcoin the token which runs on the Bitcoin network!

### Key terminology and concepts

To understand Bitcoin, you'll need to be familiar with some core terminology:

* Blockchain: A chronological chain of blocks containing bitcoin transactions. Each block references the hash of the previous block, forming a chain back to the genesis (original) block.
* Mining: The process by which new bitcoin blocks are created, transactions are confirmed, and new bitcoins are issued.
* Node: A computer running Bitcoin software that fully validates transactions and blocks. Nodes form the backbone of the Bitcoin network.
* Private Key: A secret number that allows bitcoins to be spent. Private keys are often represented as a seed phrase.
* Public Key: Derived from the private key, this is used to derive your bitcoin addresses. If anyone else is in possession of your public key, they can generate all of your addresses, so this is a privacy concern to be aware of.
* Wallet: Software that stores your private/public key pair and allows you to interact with the Bitcoin network to send and receive coins.

### Definition snippet:

* UTXO (Unspent Transaction Output): Each Bitcoin transaction consumes UTXOs as inputs and creates new ones as outputs. Your wallet balance is the net sum of your UTXOs (transactions in and out of your wallet).

### History and evolution

Bitcoin emerged in the wake of the 2008 financial crisis. On October 31, 2008, Satoshi Nakamoto published the Bitcoin whitepaper to a cryptography mailing list, proposing a new electronic cash system that would be fully peer-to-peer, with no trusted third party.&#x20;

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXf2sTDGlWYjcFAJkh2kJ8I66A2HE52lxj6dYleOckhBMQDB13mtkroiL5lbpsm7aGI-DnBWc3hrr9UCNF9-gy0NemLH0yJb4POUi9CeoN2py3Zetfbq5IHhFnuvlIQTFbQyGepxZg?key=NzQC2kWUtx6F2vKKLceZUg" alt=""><figcaption></figcaption></figure>

Satoshi announced Bitcoin for the first time on [P2P foundation](https://p2pfoundation.ning.com/forum/topics/bitcoin-open-source).

#### Historical Context Snippet:

* The first Bitcoin block, known as the genesis block, included the text "The Times 03/Jan/2009 Chancellor on brink of second bailout for banks" in the coinbase parameter. This references a headline from The Times newspaper and is widely interpreted as a message about the instability caused by fractional-reserve banking.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXeuMfRa0dcRJwBNl_qgxFXfHASLgEmMN8QGhB3kJfPqWyOicppr-hIkcS5FuPXBWSO-9AVArWqM3N6hOF0vz59fuzOOx8kL-uLl_L7n2GzYTmMVp5xPYjbX8XCFGW8Bf81PG_W5?key=NzQC2kWUtx6F2vKKLceZUg" alt=""><figcaption></figcaption></figure>

The Bitcoin Genesis block.

Since those early days, Bitcoin has weathered numerous challenges and evolved significantly. Some key milestones:

* 2010: The first known commercial transaction using Bitcoin takes place when programmer Laszlo Hanyecz trades 10,000 BTC for two Papa John's pizzas.
* 2011: Bitcoin reaches parity with the US dollar.
* 2012: The Bitcoin Foundation is created to accelerate Bitcoin's global growth and uptake.
* 2014: The IRS declares Bitcoin property for tax purposes.
* 2017: Bitcoin reaches $20,000 per coin in December, a new all-time high.
* 2021: El Salvador becomes first country to adopt Bitcoin as legal tender.
* 2024: Spot Bitcoin ETFs Approved

Throughout its history, Bitcoin development has remained decentralized, with hundreds of contributors working to improve the protocol and ecosystem as volunteers.

## Understanding the blockchain

At the heart of Bitcoin is the blockchain—a distributed ledger that records all transactions. It's essential to understand how the blockchain works, as it is part of the innovation that allows Bitcoin to function without centralized control.

* Transactions are broadcast to the network and collected into blocks by miners.
* Each block contains a hash of the previous block, forming a chain.
* As new blocks are mined, they extend the chain and increase the difficulty of modifying past blocks.
* The blockchain is shared among all nodes and continuously updated so that every node has the same copy.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdoDjSN9K9LBtzCQLaTAjBvzQtEd6MT0fAeMTBPiodt3VcGsq-zW89tvQcItBSvIaqiPaa18rskF5CP9vkK5IYx_k16iMMYfZ3EcX9hHzaaLefXm3XU8iP8wpSRaqKnRgCmnQ4q?key=NzQC2kWUtx6F2vKKLceZUg" alt=""><figcaption></figcaption></figure>

This structure provides Bitcoin with its key attributes of being tamper-evident, transparent, and immutable. Once a transaction is sufficiently deep in the chain (usually after 6 confirmations), it becomes computationally impractical to reverse, giving Bitcoin transactions a high degree of finality in a short period of time.

Personal recommendation: To really grasp how the blockchain works, we recommend exploring a block explorer site like [mempool.space](http://mempool.space). Look at some recent blocks and follow the chain of hashes to see how they're linked.

#### Advanced Cryptographic Concepts and Transaction Example

Bitcoin’s security relies on the SHA-256 hashing algorithm and ECDSA (Elliptic Curve Digital Signature Algorithm) for signing transactions. SHA-256 ensures that all data on the blockchain remains immutable, while ECDSA ensures transaction authenticity.

* Understanding ECDSA: Bitcoin uses ECDSA to generate unique public-private key pairs. The public key is derived from the private key using elliptic curve calculations, providing a robust way to validate ownership without revealing sensitive information.
* Transaction ID Generation: A transaction ID (TXID) is generated through hashing the serialized transaction data twice with SHA-256. For example, if a transaction outputs 0.01 BTC to a recipient, the details (e.g., inputs, outputs, signatures) are serialized, hashed twice, and the result is a unique identifier for that transaction.
