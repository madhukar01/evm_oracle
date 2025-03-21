# Ethereum LLM Oracle Network

A decentralized oracle network enabling Ethereum smart contracts to securely interact with Large Language Models (LLMs).


## Overview

This project implements a decentralized oracle network that bridges the gap between deterministic blockchain smart contracts and non-deterministic Large Language Models. Built on the Polygon ZKEVM testnet, the system uses a Practical Byzantine Fault Tolerance (PBFT) consensus mechanism to handle LLM outputs reliably and securely.

## Key Features

- **Decentralized Oracle Network**: 7-node network with PBFT consensus
- **Smart Contract Integration**: Solidity contracts for query submission and response handling
- **IPFS Storage**: Efficient off-chain storage with on-chain hash references
- **Response Validation**: Semantic similarity scoring using cosine similarity
- **Docker Support**: Containerized oracle nodes for easy deployment
- **Error Handling**: Robust fallback mechanisms for node failures
