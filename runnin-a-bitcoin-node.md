# Runnin a Bitcoin node

## Importance of running a node

In Bitcoin, nodes are the individual points in the network that receive, validate, and relay transactions and blocks. They are the collective guardians of the blockchain.

Running your own Bitcoin node offers several benefits:

* Sovereignty: Your node independently verifies all transactions and blocks. You don't need to trust anyone else for information.
* Privacy: By submitting your own transactions through your node, you don't reveal your financial information to other nodes.
* Security: Your node will reject any invalid transactions or blocks, preventing you from accepting bad payments.
* Network Support: By running a node, you contribute to the decentralization and robustness of the Bitcoin network as a whole.

Running a node is the most sovereign way to use Bitcoin. It's the ultimate form of "don't trust, verify".

Definition snippet:

* Full Node: A Bitcoin node that fully validates transactions and blocks. Almost all full nodes also help the network by accepting transactions and blocks from other full nodes, validating those transactions and blocks, and then relaying them to further full nodes.

## Different types of nodes

There are several types of Bitcoin nodes, each with different resource requirements and capabilities.

* Full Node: Validates every block and transaction, and keeps a complete copy of the blockchain. This is the most secure and sovereign type of node, but also has the highest resource requirements.
* Pruned Full Node: Same as a full node, but deletes older blocks to save disk space. Still validates everything, but can't serve the full blockchain to other nodes. A good option if disk space is limited.
* Lightweight (SPV) Node: Downloads block headers only, trusting that the transactions in a block are valid if the block is valid. Requires less resources, but sacrifices some security and privacy.

For most individual users, running a pruned full node offers a good balance of sovereignty, security, and resource efficiency.

Personal recommendation: If you have an always-on computer or raspberry pi with \~500GB of free disk space and a good internet connection, consider running a full archival node. You'll be contributing to the resilience of the Bitcoin network.

## Setup and maintenance

Setting up a Bitcoin node requires some technical know-how, but there are many guides and resources available to help.

Basic steps:

1. Get a machine with sufficient resources (disk space, RAM, bandwidth).
2. Install the node software. Bitcoin Core is the most common.
3. Configure the software. This includes setting up the data directory, configuring the network settings, and adjusting any other settings.
4. Start the node and let it sync with the network. This can take several days for a new full node.
5. Secure the node. Configure the firewall to only allow necessary connections, secure the machine physically, and keep the software updated.

Maintenance tasks:

* Monitor the node to ensure it's running correctly and staying in sync.
* Keep the node software and operating system updated.
* Ensure the node machine is secure and not compromised.
* Monitor disk space usage, especially for pruned nodes.

There are also more user-friendly node packages like Umbrel or Nodl that simplify setup and maintenance for less technical users.

Personal recommendation: Running a node is a great learning experience and contribution to the network. Start with a pruned node setup to familiarize yourself with the process before considering an archival node.

## Advanced Node Configuration with Tor and Pruning

For enhanced privacy and storage management, consider setting up your Bitcoin Core node with Tor routing and pruning enabled.

Configuring Tor:

1. Install Tor on the node’s host system.
2. Enable Tor proxy in Bitcoin Core by adding proxy=127.0.0.1:9050 to bitcoin.conf.

Pruning Setup:

1. Enable pruning by setting prune=550 in bitcoin.conf to reduce blockchain storage requirements.
2. This will keep only the latest 550MB of blocks, which is sufficient for verification while saving space.

Example: Running a pruned, Tor-routed node minimizes storage costs and enhances privacy by concealing your IP address from the Bitcoin network.
