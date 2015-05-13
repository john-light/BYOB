# Chapter 1: The Blockchain

## Background
The most important and fundamental tool of a bank is a ledger, a written record of transactions and balances for each account held at the bank. Without this ledger, it would be difficult if not impossible to keep track of the ownership of assets and liabilities of both the bank's customers and the bank itself. Similarly, a ledger is also fundamental to bitcoin. This ledger is called a “blockchain” and stores a complete record of every transaction that has been accepted by the bitcoin network since the launch of the “genesis block” at the beginning of bitcoin's existence. The blockchain is stored and maintained by bitcoin “full nodes,” which are required for broadcasting and relaying transactions on the bitcoin network.  

![the blockchain](blockchain.png "Simplified bitcoin blockchain.")  
<i>Simplified bitcoin blockchain.[^5]</i>  

While the legacy banking system relies on “correspondents” and other intermediaries to move funds between banks when there is no direct connection, bitcoin instead relies on a system of peer-to-peer connections between full nodes to relay transactions to miners, and then relay blocks from miners back to the rest of the bitcoin network. After a block has been accepted as valid by a majority of nodes on the network, it will be added to the blockchain, and miners will then begin building the next block with the latest batch of transactions. New entrants to the bitcoin network will only accept the longest blockchain as valid, making it very difficult for someone to trick new nodes into downloading an inaccurate blockchain. More information on the process of building blocks and adding them to the blockchain is included in Chapter 2.  

## Bitcoin Core  
The easiest way to run a full node and maintain your own copy of the blockchain is to download and run Bitcoin Core.1 2 This software will connect to peers in the bitcoin network and begin downloading and verifying blocks from each of them, eventually assembling a full copy of the bitcoin blockchain. As of the time of writing this First Edition, the full bitcoin blockchain is just over 37 gigabytes in size.



