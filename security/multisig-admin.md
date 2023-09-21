---
description: This page talks about the timelock admin contract that governs SandySwap
---

# MultiSig Admin

To enhance the security of our community's operations, we have introduced a time lock feature for all administrative functions, including proxy contracts. This time lock mechanism is managed through a multi-signature contract.

A time-locked multi-signature administration is an essential measure to safeguard the protocol until it can be replaced by a decentralized governance system.

In order to propose and execute a transaction, it is imperative that a consensus is reached among a minimum of two out of three authorized parties. The proposed transaction only becomes executable after a prescribed 24-hour waiting period. This waiting period may be extended if it is deemed necessary for added security.

Here are the contract addresses for reference:

- Timelock Contract: [0xaabea4fa7ae9f6bf1e1bc71c17fbfbd5f7b25491](https://zkevm.polygonscan.com/address/0xaabea4fa7ae9f6bf1e1bc71c17fbfbd5f7b25491)
