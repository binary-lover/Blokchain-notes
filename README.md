# Blockchain 

### Description
Blockchain is a decentralized, distributed ledger that records the provenance of a digital asset. It is a chain of blocks that contain data, with each block containing a hash of the previous block. The data in a block cannot be altered without altering all subsequent blocks, which requires the consensus of the network majority. This makes blockchain secure and tamper-proof.

### Bitcoin
- It was first introduced in 2008 by an unknown person or group of people using the name Satoshi Nakamoto.
- this network is a peer-to-peer network that allows users to send and receive bitcoins.
- this network is powered by cryptography and decentralized network of computers.
- allow people to engage cencership-resistant transactions.
- here is pdf of white paper of bitcoin: [click here](https://bitcoin.org/bitcoin.pdf).

### Ethereum

- It was proposed by Vitalik Buterin in late 2013 and development was crowdfunded in 2014.

- It is a decentralized platform that runs `smart contracts`(decentralize agreement) : applications that run exactly as programmed without any possibility of downtime, fraud or third party interference.

- It is a blockchain with a built-in Turing-complete programming language, meaning that it can run applications that are capable of performing any operation.

- **smart contracts**: is an Agreement, contract or set of instruction exceuted in decentralized way without the need of centralize of third party intermidiary.
    - Cann't be altered (immutable)
    - Automatically executed
    - Everyone can see the terms of the agreement

`Note`: Blockchain cann't read or write data from the outside world, it can only read and write data to its own blockchain. This is called oracle problem. 

Here comes `Chainlink` which is a decentralized oracle network that enables smart contracts to securely interact with real-world data, events and payments.

### Blockchain Oracles : 
- Any device that interraacts with the off-chain world and provides external data or coomputation to smart contracts on the blockchain.

`Note` we cann't work with single oracle, as we want to stay decentralized, we need multiple oracles to provide the same data. Here comes `Hybrid Smart Contracts`

* **Hybrid Smart Contracts :** Combining on-chain Decentralized logic with off-chain real-wrold data
