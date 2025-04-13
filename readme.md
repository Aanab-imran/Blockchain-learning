## Introduction:
Overview of Cyfrin Updraft!
Solidity and Smart Contract developers.
Fast-tracking learning with AI tools.
### What to Expect in the Course
Learning about DeFi, NFTs, DAOs, Tokens, Upgradeable Smart Contracts and more.
### Best practice
Use the GitHub Repo
Complete the Optional Challenges
mindset for success
Understand Blockchain and Smart Contracts
### resources 
Written Lessons Available next to the video lesson 
### Best Practices for Learning
Engage with the Community
Take Regular Breaks:
Give your brain time to absorb the material
Adjust Video Speed
Use Subtitles
### ZKsync Benefits
Increase transaction speed
Reduce transaction costs
### Bitcoin and Blockchain
Bitcoin: A digital currency using blockchain technology for peer-to-peer transactions without intermediaries.
Blockchain: A decentralized digital ledger storing transaction data across many computers.
### Ethereum and Smart Contracts
Ethereum: A blockchain that supports decentralized transactions, organizations, and agreements through smart contracts.
Smart Contracts: Self-executing contracts with terms written in code, enabling decentralized execution without intermediaries.
### The Oracle Problem
Oracle Problem: Smart contracts can't access real-world data
### Terminology
Blockchain
Oracle
Layer 2
Dapp (Decentralized Application)
Smart Contract
Hybrid Smart Contract
Ethereum/EVM

## Features of Smart Contracts
### Decentralization
No centralized intermediary; runs on a blockchain maintained by many node operators.
### Transparency and Flexibility
Transparent ensuring fairness without compromising privacy.
### Speed and Efficiency
Faster than traditional banking systems blockchain transactions are nearly instant.
### Security and Immutability
Once deployed, smart contracts can't be altered. Blockchain's decentralized nature makes hacking difficult.
### Elimination of Counterparty Risk
No trust required; terms can't be changed once the contract is deployed.

### Applications of Smart Contracts
### Decentralized Finance (DeFi)
Enables financial transactions without intermediaries offering transparent access to markets.
### Decentralized Autonomous Organizations (DAOs)
Governed by smart contracts, providing transparent and decentralized governance.
### Non-Fungible Tokens (NFTs)
Digital unique assets or art, enabling creators to monetize their work.
### Other Applications
Potential for new innovations in smart contract uses.
### MetaMask Wallet Setup 
### Switch to Test Network
### Sending Your First Transaction:
Create New Account in MetaMask
### Testnets Overview:
 Tenderly is our preferred virtual testnet tool for deploying smart contracts and making transactions.
 ### Testnet Transactions:
Learn how to send transactions on a testnet
### Testnet Exploration:
Explore testnet explorers like Etherscan or Blockscout
## Testnet Basics:
Sepolia is a popular testnet for experimenting with transactions without real money
#### Connecting Wallet to Faucet
## Transaction Fee and Gas Price:
### Transaction Fee:
The amount rewarded to the block producer for processing the transaction
it is paid in Ether or GWei.
### Gas Price:
Gas price is the cost per unit of that effort.
#### Connecting Wallet to Faucet


###  Nodes in Blockchain


### Gas in Transactions:
 Gas signifies a unit of computational complexity
 ### Transaction Fee:
  Calculated as:

Transaction Fee = Gas Price * Gas Used
### Hash
A unique fixed length string, mean to identify a piece of data.they are created by placing said data into a "hash function"
 Ethereum uses Keccak-256 
 Mining is the process of finding a nonce that generates a hash matching a certain condition
 ### Blockchain: Immutability
A blockchain is a linked chain of blocks
### Genesis Block: 
This is the first block in a blockchain
### Blockchain & Transactions
The data inside real blockchain blocks usually consists of transactions
Multiple transactions are grouped and hashed together
### Private key
only known to the key holder its used to "sign"transaction.
A private key is a randomly generated secret key used to sign all transactions
The private key must remain secret
### Public key
public key is derived from your private key anyone can see it and use it to verify that a transaction came from you.
Public keys are visible to everyone on the blockchain
### Signing a Transaction
A one way process someone with a private key signs a transaction by their private key being heshed with the transaction data
The signature can be verified by anyone using the corresponding public key
### Importance of Hiding Private Keys
Access your wallet
Sign and send transactions
### What is Gas in Blockchain?
Gas is the unit of computation required to perform actions on the Ethereum blockchain (e.g., sending ETH, executing smart contracts)
##  Transaction Breakdown
### Transaction Fee
Transaction Fee = Gas Used × Gas Price
###  Gas Limit
The maximum gas allowed for the transaction
Set by the user before sending
###  Base Fee
The minimum cost per gas unit, shown in Gwei.
Introduced in EIP-1559
Burnt after each transaction — removed from circulation to fight inflation
### Max Gas Fee
The maximum a user is willing to pay per gas unit
## Blockkchain Overview
#### Node 
A single instance in a decentralized network
### traditional network
 controlled and run by a single centralized group
 ###  Consensus
Consensus is the mechanism used to reach an agreement on the state or a single value on the blockchain, especially in a decentralized system
### Blockchain Attacks
Sybil Attack  When a user creates a number of pseudo-anonymous accounts to try to influence a network
51% Attack One entity controls majority hash power; can double-spend or alter blockchain history
### Layer1:
Base layer of the blockchian ecosystem in which transactions are executed and confirmed
### Layer2
layer2 is any application built on outside an L1 blockchain that hooks back into it
### Blockchain Rollup:
Scaling sloution that increases the number of transaction on the L1 chain
### Optimistic Rollups:
Optimistic Rollups assume that the off-chain transactions are valid by default(Assume transactions are legitimate)
Use fraud proof to verify correctness in the case of dispute
### zk Rollups: (Zero knowledge)
Zk Rollups solution prove each transaction bach to be correct using validity proofs or Zk proofs
ZK proofs are the complex mathematical cryptographic problem
### ZK proofs involves two participants:
#### Prover
That is trying to prove that they know something
#### Verifier
That is verifying that the prover does in fact know the answer to the problem
### Sequencer
The sequencer usually refers to the operator which is ordring the transactions bundling them together
### Rollup Stage
Stage of a rollup is a categorization framework based on Vitalix proposed milestones
#### Stage 0 (Full traning wheel)
In stage 0 the operators and a security council predominantly manage the rollup
Open source software for data  avalibility
### Data avalibility
Data avalibility refers to the confidence a user can have that the data required to verify a block really is avaliable to all network participants
### Stage 1(Enhanced Rollup Governance)
Governed by small contracts 
Security council for bug resolution
### Stage 2 (No Traning wheels)
Completed Decentralized
Smart contract manage the rollup
Ample time to exit system in the case of upgrades

# Solidity Smart Contract Development
