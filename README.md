# Study Nodes of Ethereum

This is a small and modest repository of ethereum study notes. This helps me understand the technology behind ethereum and also improve my ugly English.
All grammar fixes and any other contributions are always welcome.


## Blockchain

* Network of nodes sharing same information.
* Ledger or register distributed in all nodes.
* This network not have any point of failure.
* Each block is linked to the previous block in the chain.

## Block

All blocks have same properties.

* Block Header
  - Hash of the previous block.
  - Timestamp
  - Defficulty level
  - Nonce (POW)
  - Root Hash of transactions block (Merkle tree)

* Block of transactions
  - All hashes of transactions in a block form a Merkle tree.

## Double Spending

Double spending is an operation where the same transaction is made twice. 

### How does bitcoin prevent double-spending?

* Bitcoin has built-in mechanisms to deal with such attacks. 
* A lot of computing power is used to validate the transaction.
* The more confirmations, the less chance of falsification.

# Hashing

Hashing is an algorithm that takes any string as input and gives you
another string as output that has a fixed length.