# Blockchain_document
1. Programming blockchain 
+ Overview bitcoin of blockchain 
+ Write transaction bitcoin with C#
+ Build Wallet bitcoin with C# 
Foreword
Second (Community) Edition
Introduction
Why Blockchain Programming and not Bitcoin Programming?
Why C#?
Why this book?
Crowdfunding this book
Complementary reading
Diagrams
License: CC (ASA 3U)
Prerequisites
Project setup
Bitcoin transfer
Bitcoin address
ScriptPubKey
Private key
Transaction
Blockchain
“The Blockchain is more than just Bitcoin”
Spend your coin
Proof of ownership as an authentication method
Key generation and encryption
Is it random enough?
Key Derivation Function
Like the good ol’ days
BIP38 (Part 2)
HD Wallet (BIP 32)
Mnemonic Code for HD Keys (BIP39)
Dark Wallet
Other types of ownership
P2PK[H] (Pay to Public Key [Hash])
P2WPKH (Pay to Witness Public Key Hash)
Multi Sig
P2SH (Pay To Script Hash)
P2WSH (Pay to Witness Script Hash)
P2W* over P2SH
Arbitrary
Using the TransactionBuilder
Other types of asset
Colored Coins
Issuing an asset
Transferring an asset
Unit tests
Ricardian contracts
Liquid Democracy
Proof of Burn and Reputation
Protecting your private keys

2. Packt.Building.Blockchain.Projects
+Building Blockchain Decentralized Project 
Chapter 1: Understanding Decentralized Applications 
What is a DApp? 
Advantages of decentralized applications 
Disadvantages of decentralized applications 
Decentralized autonomous organization 
User identity in DApps 
User accounts in DApps 
Accessing the centralized apps 
Internal currency in DApps 
Disadvantages of internal currency in DApps 
What are permissioned DApps? 
Popular DApps 
Bitcoin 
What is a ledger? 
What is blockchain? 
Is Bitcoin legal? 
Why would someone use Bitcoin? 
Ethereum 
The Hyperledger project
IPFS 
How does it work? 
Filecoin 
Namecoin 
.bit domains 
Dash 
Decentralized governance and budgeting 
Decentralized service 
BigChainDB
OpenBazaar
Ripple
Chapter 2: Understanding How Ethereum Works 
Overview of Ethereum 
Ethereum accounts 
Transactions
Consensus
Timestamp
Nonce 
Block time
Forking
Genesis block
Ether denominations
Ethereum virtual machin
Gas
Peer discovery
Whisper and Swarm
Get
Installing geth
OS X 
Ubuntu
Windows
JSON-RPC and JavaScript console
Sub-commands and options 
Connecting to the mainnet network 
Creating a private network 
Creating accounts 
Mining 
Fast synchronization 
Ethereum Wallet 
Mist 
Weaknesses 
Sybil attack 
51% attack 
Serenity
Payment and state channels 
Proof-of-stake and casper
Sharding
Chapter 3: Writing Smart Contracts 
Solidity source files 
The structure of a smart contract
Data location 
What are the different data types? 
Arrays 
Strings 
Structs 
Enums 
Mappings 
The delete operator 
Conversion between elementary types
Using var 
Control structures 
Creating contracts using the new operator 
Exceptions 58
External function calls 
Features of contracts 
Visibility 
Function modifiers 
The fallback function 
Inheritance 
The super keyword 
Abstract contracts 
Libraries
Using for
Returning multiple values
Importing other Solidity source files
Globally available variables
Block and transaction properties 
Address type related 
Contract related 
Ether units 
Proof of existence, integrity, and ownership contract 
Compiling and deploying contracts 
Chapter 4: Getting Started with web3.js
Introduction to web3.js
Importing web3.js 
Connecting to nodes
The API structure
BigNumber.js 
Unit conversion 
Retrieving gas price, balance, and transaction details
Sending ether 
Working with contracts 
Retrieving and listening to contract events 
Building a client for an ownership contract 
The project structure
Building the backend
Building the frontend
Testing the client 
Chapter 5: Building a Wallet Service 
Difference between online and offline wallets 
hooked-web3-provider and ethereumjs-tx libraries 
What is a hierarchical deterministic wallet? 
Introduction to key derivation functions 
Introduction to LightWallet 
HD derivation path 
Building a wallet service
Prerequisites 
Project structure 
Building the backend 
Building the frontend 
Testing 
Chapter 6: Building a Smart Contract Deployment Platform 
Calculating a transaction's nonce 
Introducing solcjs 
Installing solcjs 
solcjs APIs 
Using a different compiler version 
Linking libraries 
Updating the ABI 
Building a contract deployment platform 
The project structure 
Building the backend 
Building the frontend 
Testing 
Chapter 7: Building a Betting App 
Introduction to Oraclize 
How does it work? 
Data sources 
Proof of authenticity 
Pricing 
Getting started with the Oraclize API 
Setting the proof type and storage location 
Sending queries 
Scheduling queries 
Custom gas 
Callback functions 
Parsing helpers 
Getting the query price
Encrypting queries
Decrypting the data source
Oraclize web IDE 
Working with strings 
Building the betting contract 
Building a client for the betting contract
Projecting the structure 
Building the backend
Building the frontend 
Testing the client 
Chapter 8: Building Enterprise Level Smart Contracts 
Exploring ethereumjs-testrpc 
Installation and usage 
The testrpc command-line application 
Using ethereumjs-testrpc as a web3 provider or as an HTTP server 
Available RPC methods 
What are event topics? 
Getting started with truffle-contract 
Installing and importing truffle-contract 
Setting up a testing environment 
The truffle-contract API 
The contract abstraction API 
Creating contract instances 
The contract instance API 
Introduction to truffle 
Installing truffle 
Initializing truffle 
Compiling contracts
Configuration files
Deploying contracts 
Migration files 
Writing migrations 
Unit testing contracts 
Writing tests in JavaScript 
Writing tests in Solidity
How to send ether to a test contract 
Running tests 
Package management 
Package management via NPM 
Package management via EthPM 
Using contracts of packages within your contracts 
Using artifacts of packages within your JavaScript code 
Accessing a package's contracts deployed addresses in Solidity 
Using truffle's console 
Running external scripts in truffle's context 
Truffle's build pipeline 
Running an external command
Running a custom function
Truffle's default builder 
Building a client 
Truffle's server 
Chapter 9: Building a Consortium Blockchain 
What is a consortium blockchain? 
What is Proof-of-Authority consensus? 
Introduction to parity 
Understanding how Aura works 
Getting parity running 
Installing rust
Linux 
OS X 
Windows 
Downloading, installing and running parity 
Creating a private network 
Creating accounts
Creating a specification file
Launching nodes
Connecting nodes 
Permissioning and privacy 

