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
### introduction
Accounts You Should Have
#### GitHub (For code + discussions)
#### Stack Exchange Ethereum (For dev-level questions)
#### ChatGPT (AI explanations) 
#### Google Gemini  (Free AI that also understands YouTube videos)
### Remix IDE
Online tool for writing, compiling, and deploying Solidity smart contracts
### What is Compiling?
Converts your Solidity code (human-readable)Bytecode (machine-readable)
Required to deploy on blockchain
 ### Elementary Data Types in Solidity
 #### Boolean (bool): true or false
 like someone have active account or not
 bool isActive = true;
 #### Unsigned Integer (uint,unit256)
 
 if you wrote unit only it is consider 256
 Address (address): 20 bytes value
 e.g; 
 uint256 age = 25;
uint amount = 100;
 Bytes (bytes): low-level raw byte data
 ### signed intiger (int, int256)
it take both positive and negative
someone balance is also -100
int256 balance = -50;
 ### Address (address)
 it is always 20 bytes 
 Ethereum address (the address of a wallet or a smart contract)
It is mostly used to send funds to someone or to interact with a smart contract
address myWallet = 0xAbC123...;
### String (string)
it store text or words
its is dynamic(not fixed in size)e.g name of a user or message
string name = "Alice";
### Bytes (bytes, bytes32)
Used to store low-level data, such as raw hexadecimal values.
bytes32 means a fixed-size array of 32 bytes.
bytes is dynamic, meaning it can change in size depending on the data.
### Bytes vs Strings
Feature    	       bytes                     	             string
Format    	       Hexadecimal	                           Text-based
Type             	 Low-level, raw data	                   High-level, dynamic text
Flexibility	       Fixed (bytes1 - bytes32) or dynamic     Always dynamic
### Function in Solidity
Functions are blocks of code to perform specific tasks
Arrays store values without identity
No way to link a number with a person's name
### Error
Errors must be fixed before deployment
### Warnings 
 bad practices, but code still works. You should still fix them
 #### Calldata
Calldata variables are read-only and cheaper than memory. They are mostly used for input parameters
### Mapping
A mapping is defined using the mapping keyword, followed by the key type, the value type, the visibility, and the mapping name
##  Deploying a Solidity Contract to a Testnet
### Testnet
A testnet is a public blockchain network used for testing purposes. It behaves like the mainnet but uses test ETH, which has no real-world value
####  Final Checks Before Deployment
#### Connect MetaMask to Remix
#### Switch to Sepolia Testnet
#### Get Test ETH
#### Deploy the Contract
####  View Contract on Etherscan

### zkSync Deploying
#### zkSync Faucet
Similar to Sepolia faucet Provides free test ETH for zkSync testnet May be unreliable at times
#### zkSync Bridge
Transfers test ETH from Ethereum Sepolia to zkSync Testnet More reliable than faucet Requires ETH in Sepolia and a bridging transaction

### zkSync Bridging
 Connect MetaMask to zkSync Bridge
 Get Sepolia ETH 
 Bridge to zkSync
 Transfer Funds
 Add zkSync Sepolia to MetaMask
Visit Chainlist

### zkSycn Plugin 
#### Compile the Contract
Use Solidity version 0.8.24 to match zkSync compiler requirements
#### Deploy the Contract
MetaMask will prompt you for a signature – approve it
#### Verify the Contract
This confirms that the contract is deployed and verified
#### Check on zkSync Sepolia Explorer
 zkSync Sepolia Block Explorer to..
 As of now, the zkSync plugin has a minor bug. Refer to Lesson 14 for a workaround

 ### zkSycn Plugin Fix
 After successful compilation, zkSync plugin may still show:
no smart contracts ready for deployment

### zkSycn interactions
#### functions
addPerson
listOfPeople
nameToFavoriteNumber
retrieve
store

#### EVM 
Ethereum Virtual Machine
Allows contracts to run on EVM-compatible blockchains like
Ethereum
Polygon
Arbitrum
Optimism
zkSync
Common types: uint256, bool, string
Custom types: struct
Collections: array, mapping

### Storage Factory introduction
All thee Github repos associated with this course end with f12 which stands for foundry 2023
#### SimpleStorage.sol
The base contract for storing a favoriteNumber
#### AddFiveStorage.sol
Inherits from SimpleStorage, with added logic
#### StorageFactory.sol
Manages and interacts with multiple deployed instances of SimpleStorage
Index 0 :First deployed SimpleStorage
Index 1 : Second deployed SimpleStorage, and so on

### Composability
Composability is the ability of smart contracts to interact with one another seamlessly and permissionlessly
It's allowed to have multiple contracts in the same file

### Import
The import keyword in Solidity helps maintain clean, modular, and reusable smart contract code.
 No Cluttering: Keeps your files short and readable.
Simplified Maintenance: Update logic in one file and reflect changes wherever it’s imported
 When using import, all imported files must share compatible compiler versions.

 ###  Using AI tools 
 Using AI tools like ChatGPT or Bard can accelerate your learning, especially when used effectively.
Good AI Prompt Format

### Contract Composition via StorageFactory
Deploy multiple instances of another contract (SimpleStorage)
Keep track of those deployments
Interact with each deployed contract individually

### Inheritance 
allows one contract (child) to inherit the functions and variables of another contract (parent)
### Overriding Functions
You can customize inherited functions using the override keyword — but only if the parent function is marked as virtual
### FundMe 
The main crowdfunding contract where users can contribute and the owner can withdraw funds
### PriceConverter 
A utility contract used to enforce minimum funding amounts based on real-world currency
### fund and withdraw
After deploying the FundMe contract in Remix, you’ll notice several functions. Among them is a red fund button, which is colored red because it’s a payable function. This means it can receive native blockchain tokens

### Reverts
Definition: Reverts undo all state changes made during the transaction
###  Gas
Purpose: Measures the computational cost of running operations on the EVM
#### NOTE
 If a transaction reverts, is defined as failed
#### For Value Transfers
Nonce – Tx count of sender
Gas Price – Price per gas unit
Gas Limit – Max gas allowed
To – Recipient address
Value – ETH amount in wei
Data – Empty
v, r, s – Signature components
#### For Contract Interactions
Same as above, except:
To – Smart contract address
Data – Contains function call + parameters

### payable
Purpose: Allows a function to receive ETH or native blockchain tokens
### msg.value
Represents the amount of ETH (or native token) sent with the transaction
### require()
Used to enforce conditions and revert if not met
### Chainlink 
Chainlink allows smart contracts to interact with external (off-chain) data in a decentralized way

### Goal
Convert  (ETH) to USD
Use Chainlink Price Feed to get current ETH/USD price
#### Source
 Chainlink Price Feed Addresses
### Interfaces in Solidity
A way to interact with external contracts without full code
Decouples your contract from external contract logic
Makes code modular, reusable, and testable

#### NPM and Github
 when interpreted by the Solidity compiler in Remix or another development environment, means “Import the AggregatorV3Interface interface from a specific file path inside the @chainlink/contracts NPM package.”

###  getPrice
The getPrice function returns the current value of Ethereum in USD as a uint256
### getConversionRate
 The getConversionRate function converts a specified amount of ETH to its USD equivalent
Always multiply before dividing to maintain precision and avoid truncation errors
Compile the contract in Remix.
Select "Injected Provider - Metamask" under the ENVIRONMENT tab in the Deploy & Run Transactions plugin.
Ensure you're connected to a testnet like Sepolia

### Tracking Funders
Track which addresses fund the contract
Track how much ETH each address sends
Track how many times each address contributes
### Mapping Address
This mapping links each address to the total amount they’ve sent
msg.value is the amount of ETH sent in the transaction
###  Tracking Number
This keeps track of how many times an address has sent ETH

### Interacting with External Contracts
To interact with a contract already deployed on the blockchain, you need
Contract Address – Identifies where the contract lives
Write an interface that matches the external contract
### Chainlink Price Feeds
Chainlink provides live price data from the real world
These are useful when your smart contract needs trusted price data
### Solidity Global Properties
These are built-in variables that give info about the blockchain, block, or transaction
msg.sender: the address of the caller (who's interacting with the contract)

###  Library in Solidity
A library in Solidity is like a helper module that stores reusable code (functions). It is ideal for extracting common logic such as price conversions or math operations
 Clean up large contracts by moving reusable functions into separate files
 ### Important Rule
If a library function is not marked internal,
The library must be deployed separately, and
The contract must link to the library at compile time (more complex and expensive)
Use internal functions in libraries to keep them embedded and simple

###  Integer Overflow
An integer overflow occurs when a number exceeds the maximum value that a variable type can store
Before Solidity 0.8.0, this operation would not trigger an error—it would silently wrap the value, causing unexpected behavior or security vulnerabilities
#### SafeMath
The SafeMath library was used to prevent overflows and underflows by checking mathematical operations and reverting if something went wrong

###  for Loop
A for loop is a control structure that runs a block of code repeatedly, usually based on an index or counter
#### Use for Loops in FundMe
In the FundMe contract, we use a for loop to reset all funders’ contributions after a withdrawal
#### Key Shortcuts Used
funderIndex++
Means funderIndex = funderIndex + 1
+=
Means x = x + y
###  Reset an Array
In Solidity, you often need to clear the contents of an array after performing an action like withdrawing funds — especially in fundraising contracts like FundMe
### Goal
To send ETH from a smart contract to an external address, Solidity offers three main methods:
transfer
send
call
#### transfer
ends ETH to a payable address
Automatically reverts the transaction on failure
Has a gas limit of 2300
Simple but outdated for many use cases
#### send
solidity
Copy
Edit
Same gas limit as transfer (2300)
Returns a boolean (true or false) instead of reverting
Manual error handling required using require
 Less safe than transfer since it doesn't auto-revert. Must check return value!
### call 
Most flexible and recommended method.
No fixed gas limit.
Can interact with both:
functions
or simply send ETH
Returns:
a boolean for success
a bytes object for return data
#### payable
Solidity requires addresses to be explicitly marked as payable in order to receive ETH.

### Constructor
A constructor is a special function that runs once, automatically, when the contract is deployed
### What are Modifiers
Modifiers are reusable code blocks that can be attached to functions
used for:
Access control
Input validation
Condition enforcement
### _ (underscore)
_ must come after the condition
If you place _ before require, it would run the function logic before the check — which is unsafe
Gas = Cost. Reducing gas used lowers the cost of deploying and using the contract
constant and immutable help reduce storage reads/writes, which are expensive operations in Ethereum
FundMe Contract 
Original deployment gas: ~859,000
### zkSycn
After compiling a contract using the ZKsync Remix plugin, the deploy tab shows
no smart contracts ready for deployment
### Adjustments for ZKsync Deployment
 Use Correct Chainlink Price Feed
Get the ETH/USD price feed address for ZKsync Sepolia from:
 Chainlink Price Feeds – ZKsync
Solidity Version Compatibility
Library Handling Issue
###  Special Functions
constructor: Initializes the contract; runs once during deployment
receive()
Triggered when ETH is sent with no data
#### 6 steps to solve any problem you may face
Tinker
 Ask Your AI
 (principle 1 Write clear and speific instruction
 principle 2 Give as much context as possible
 principle 3 Look out for hallucinations
 principle 4 Understand limitations
 principle 5 Iterate constantly)
 Read Docs
 Web Search
 Ask in a Forum
 Ask on the Support Forum or GitHub
 Iterate
#### Limit Self-Triage Time
Spend 15–20 minutes max troubleshooting an issue on your own
####  Using AI Tools
Use tools like ChatGPT to assist, but don’t rely on them fully
AI can hallucinate
#### Developer Forums
Use Stack Exchange and Peeranha for help
Format questions clearly using Markdown
Use AI to learn proper question formatting
Use GitHub as your project portfolio—important for job applications
GitHub is essential for code sharing, collaboration, and issue tracking
If you don’t have an account, create one now — it's imperative for course participation
####  Markdown Formatting
Vital for readability
Use AI tools (like ChatGPT) to help format your questions if needed
###  Scaffold-ETH 2
Tool for Solidity learners
Offers a dynamic front-end UI that syncs with your smart contract changes
Lets you visualize and interact with your code in real time





### (EASY) PROJECTS
#### 1.Simple Storage
Learned:
uint state variable
creat set and get function

### 2.Favourite Number Tracker
Learned:
use mapping(string => uint) 

### 3.Simple Counter
Learned:
arithemetic 
state mutability

### 4.To-Do List
Learned:
defie struct
array ,bool

### 5.Simple Bank
Learned:
ETH using payable and msg.value
balance tracking

### 6.Voting System
Learned:
mapping ,require(no double voting)
using if/else 

### 7.Access-Controlled Storage
Learned:
use constructor 
require (msg.sender == owner)
modifier

### 8.ETH Piggy Bank
Learned:
block.timestamp ,require

### 9. Basic NFT 
Learned:
custom ID logic 

### 10.Fund Splitter
Learned:
ETH transfers, arithematic ,payable

#### deposit
user send ETH to contract and their balance is recorded
#### Withdraw 
user requests to take back their stored ETH from the contract