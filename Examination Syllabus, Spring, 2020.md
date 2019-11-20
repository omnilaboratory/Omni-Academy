# Omni Blockchain Examination Syllabus, Spring, 2020

**Subject:**  Blockchain Theory and Application    
**Organizer:** Omni Committee on Examination  

## Chapter I. Objectives  
There is one aim for this syllabus: to instruct relatively unsophisticated programmers/audiences to understand the background, basic theory, and application of blochchain technology, grasp fundamental concepts, technical processes, specifications and their applicable scenarios. After passing this examination, audiences shall become a specialist with ability to develop blockchain products and applications. 

Total score of this examination is 600 points, with each of the following sections 100 scores.  

Section 1. Knowledge base of Blockchain        
Section 2. Bitcoin network and Omnilayer specification  
Section 3. Smart contract, Ethereum and HyperLedger  
Section 4. Lightning network, LND and OmniBOLT specification  
Section 5. Security    
Section 6. System Maintenance  

## Chapter II. Exam Syllabus  

### 1. Knowledge Base of Blockchain

1）History of blockchain  
2）Main functionalities of blockchain  
3）Major product forms   
* Public chain  
* Consortium chain  
* Private chain  
* Side chain  

4）Symmetric and asymmetric cryptographic theories    
* Elliptic curve cryptography  
* RSA theory and algorithm   
* Hash algorithms  
* Principle of digital signature  

5）Block, Chain and Graph   
* Basic structure of a block  
* Chain  
* Hard/Soft fork    
* Directed Acyclic Graph    
* Merkle tree    

6）Wallet    
* Functions of a wallet  
* Types of wallets (code wallet, hot wallet, full node wallet, light wallet, centralized/decentralized wallet)  
* Mnemonic words, public/private key pair  
* Hierarchical Deterministic Wallet  
* Process of generating mnemonic words and pub/priv key pairs  
* Restore by mnemonic words  
* Restore by importing private key  

7）Knowledge points from Satoshi’s whitepaper  
* “double spent” and how to solve    
* Chain, fork  

8）CAP(consistency, availability, partition tolerance) theory and distributed database system  
* Main modules of a database system  
* CAP theory    
* Eventual consistency  

9）Distributed storage, IPFS  
* Distributed storage and centralized storage  
a)What is DropBox, centralized or distributed?  
b)Storage with Multiple clusters Vs distributed p-2-p storage  
* Modules in a P-2-P system  
* Distributed Hash Table, Routing, Kademlia DHT, and Coral DHT   
* Consensus, RAFT  
* BitSwap Protocol  

### 2. Bitcoin Network and OmniLayer Specification

1）Characters of Bitcoin network, consensus algorithm, block structure. etc  
2）Proof of Work, Mining, and Reward  
3）Deterministic Wallets，BIP 32，39，44，45，  
4）Segregated Witness  
* What is SegWit  
* The purpose of SegWit  
* The Rules of SegWit  

5）Operation on UTXO    
* Concept of UTXO  
* How to use UTXO in constructing transactions  

6）Redeemscript  
* How redeemscript works  

7）Address  
8）Types of Bitcoin Transactions  
9）Construction of transaction and validation  
10）Principal of OmniLayer  
* What is OmniLayer  
* How OmniLayerworks  
* OP_RETURN and data structure in Omnilayer specification  
* Deployment of Omnicore  
* RPC  

11）OmniLayer address types and transactions  
* OmniLayer address and Bitcoint address  
* Transaction construction  
* Comparison of OmniLayer transaction and Bitcoin transaction  
* Assets on OmniLayer  

12）Omni DEX specification  


### 3. Smart Contract

1）Turing completeness Vs incompleteness  
* What is Turing Completeness  
* Scenarios of the two types of languages  

2）Principal of Smart Contract  
* Process of execution of smart contract, using EVM/Ethereum as an example  
* Interfaces of ERC 20 compatible contracts   

3）Case study: HyperLedger Chaincode  
4）Compose, compile, deploy and validate contracts      
* Write a real contract for Ethereum and HyperLedger    
* Deploy the contract to the Eth/HyperLedger network  
* Test and validate contract   
* Fix bugs and flows  

5）Design a smart contract system  
* Function modules  
* Execution process: compile, deploy, run and validate.  

### 4. Lightning Network

1）Background of Layer two protocols   
2）Principal of lightning network    
* Differences between On-chain and off-chain transaction  
* Comparison between main layer two protocols and lightning network  

3）Revocable Sequential Maturity Contract  
* Main steps in RSMC  
* Punishment of malicious player, the complete process  

4）Hashed TimeLock Contract  
* Purpose of HTLC  
* Main steps in HTLC  
* Routing algorithms  
* Transactions: BR，RD，HED，HT，HBR，HTRD，HTBR  
* Closing HTLC  

5）Main functions implemented by LND  
6）Characters of OmniBOLT  
7）Construction OmniBOLT transaction  
8）OmniBOLT channel   
* WebSocket  
* Poon-Dryja Channel creation, exchanging, transferring, and closing  
* Deploy and run an OBD (OmniBOLT Daemon)  


### 5. Security of Blockchain System

1.Security of Linux System  

2.Private/Public key pair  
* How to generate keys  
* How to store keys  

3.Mnemonic words, Hierarchical Deterministic Wallet    
* HD - Hierarchical Deterministic    
* process of generate mnemonic words  
* Why mnemonic words   

4.Security of the following Scenarios  
* List weakness of all kinds of wallet   

5.White list of OmniLayer  
* What is whitelist system?  
* Function of a whitelist system  

### 6.System Maintenance 
1.Maintenance of Linux system  

2.How to setup an OmniLayer/BTC full node?  
* Deploy a BTC full node    
* Deploy an OmniLayer full node  

3.How to synchronize data? What are prerequisites?  
* Process of running a OmniLayer full node  
* Network, port, server configuration  

4.How to monitor node status?  
* main RPC in querying node status  

5.Typical error check    
* Typical error explanation    
* How to solve  

6.How to create/maintain accounts/addresses  

7.Using cli to construct BTC transaction and Omnilayer transaction  
* RPC commands and analysis   
* Steps in construction    

8.How to query the status of transactions  
* RPC command  
* Using third party block explore to check the status of a curtain transaction  

9.Typical errors in constructing transactions  
* List of typical error  
* Methods in fixing error

## Chapter III. Exam Information
**1.Duration:** 100 minutes per section   
**2.Score:** 100 points  
**3.Types of Questions:** Essay-type Questions, Code snippets to proof logic   

## Chapter IV. Curriculum  
The material covered in this exam is now included within the curriculum provided by officially appointed training agencies or learning facilities.
	
