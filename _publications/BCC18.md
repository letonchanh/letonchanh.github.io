---
title: "Proving Conditional Termination for Smart Contracts"
collection: publications
permalink: /publications/BCC18
venue: 'BCC@AsiaCCS 2018'
date: 2018-06-04
authors: '<b>Ton Chanh Le</b>, Lei Xu, Lin Chen, Weidong Shi:'
proceedings: '<i>The 2nd ACM Workshop on Blockchains, Cryptocurrencies and Contracts</i>'
confurl: https://sites.google.com/view/bcc18/home
paperpdf: http://letonchanh.github.io/files/bcc18.pdf
---

## Abstract
Termination of smart contracts is crucial for any blockchain system's security and consistency, especially for those supporting Turing-complete smart contract languages. Resource-constrained blockchain systems, like Ethereum and Hyperledger Fabric, could prevent smart contracts from terminating properly when the pre-allocated resources are not sufficient. The Zen system utilizes the dependent type system of the programming language F* to prove the termination of smart contracts for all inputs during compilation time. Since the smart contract execution usually depends on the current blockchain state and user inputs, this approach is not always successful. In this work, we propose a lazy approach by statically proving conditional termination and non-termination of a smart contract to determine input conditions under which the contract terminates or not. Prior to the execution of the smart contract, the proof-carrying blockchain system will check that its current state and the contract's input satisfy the termination conditions in order to determine if the contract is qualified (i.e., eventually terminating) to run on the chain.
