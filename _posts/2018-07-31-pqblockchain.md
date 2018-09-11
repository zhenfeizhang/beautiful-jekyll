---
layout: post
title: The Future of Blockchain - A Lack of Authenticity and Privacy
image:
tags: [blog]
---

Originally posted [here](http://blog.onboardsecurity.com/blog/the-future-of-blockchain-a-lack-of-authenticity-and-privacy).

The Future of Blockchain - a Lack of Authenticity and Privacy
======================================================

Modern technology is all about buzz words. Unless you have been trapped in the phantom zone for the past few years, you must have heard of quantum computers and blockchains. Some say that quantum computers are the next generation of computers, and blockchains are the next generation of the Internet. What will the next generation look like when we have both quantum computers and blockchains in a same room? A quantum apocalypse.


What is a Blockchain?
------------------------------------------------

Before we start, let’s briefly recall what a blockchain is and what makes it such a phenomenon. Essentially, blockchain is the next form of a database, a “ledger”, sitting on top of a distributed system, that is not controlled by any individuals. 

At a high level, the data blocks are linked together via a hash function: the hash function compresses a block into a short image. A chain is formed by embedding the image of the previous block into the next block, and so forth. An engineering equivalent is a linked list, where each node has a field that stores the hash digest of the previous node. Next, this chain is duplicated among many participants, either publicly (public chain) or privately (alliance chain). 

The data integrity relies on the facts that 

* it is computationally infeasible to reserve the hash function, and 
* no single “trusted” party (for example, your cloud provider) is able to overwrite the consensus of the participants. 

Of course, data is not all about integrity. In most cases people are also concerned with data authenticity and privacy. Authenticity means that your data is indeed from an authorized entity, be it a service provider, or a legitimate subscriber. Privacy is a particularly concerning issue. It means no one should be able to link the data to its owner, unless they opt to. From a legal point of view, European has put forth this General Data Protection Regulation (GDPR) regulation. From a commercial point of view, we have seen how much damage privacy has done on Facebook in the past few days.



Privacy with Authenticity
------------------------------------------------

Now, let’s move a bit further into the cryptography domain. To enable authenticity and privacy simultaneously is a bit counter intuitive, as how may one endorse a piece of data, without letting people know who they are? There are two mainstream solutions which have been among the most active research fields in advanced cryptography in past years. The first solution is called ring signatures. At a high level, the signer will sign on behalf of an ad-hoc group of people, whereas the verifier is not able to single out the signer from the group. There is a special case of ring signatures, called linkable ring signatures, which, although does not reveal the identity of the signer, links a signer to all the data it previously endorsed. A very special application for this scheme is privacy preserving cryptocurrency where one can keep its identity hidden unless it spends a same token twice. This solution is indeed deployed by a few popular cryptocurrencies, such as Monero and zerocoin. The other solution is called zero knowledge proofs which essentially allows a prover to convince the verifier that the prover knows something without verifier learn anything about ‘something’. 

Cryptographic functions involved in the above techniques are hash functions, digital signatures, (linkable) ring signatures and zero knowledge proofs. A natural question to ask is how can we be assured that those schemes are indeed correct and secure? We base the schemes upon some mathematical hard problems; for instance, factoring large integers, or finding the discrete log for a group element. The security of the blockchain is then mathematically provable through a chain of reductions, in the sense that if there exists an attacker who can break the system, then this same attacker must be able to solve the hard problem that no man can solve.

Quantum Computing
------------------------------------------------

This is where quantum computer matters. The cryptography community has known since the early 90’s that those hard mathematical problems are not hard for quantum computers.  Problems that appear infeasible for classical computers will be solved within minutes or seconds with a general purpose quantum computer. Today, great progress is being made in building a quantum computer. When that day comes, the vast majority of the cryptography deployed around the world, including those for blockchains, will be broken.  Quantum computing technology is advancing rapidly. In 2015, NSA advised people to prepare for a transition to quantum-safe cryptography. In 2017, NIST started quantum-safe cryptography standardization process. Many prominent figures in cryptocurrency, such as Vitalik Buterin, founder of Ethereum, have commented that blockchain and cryptocurrency platforms are currently vulnerable and should be integrating quantum-safe techniques sooner rather than later.

So what exactly gets broken for blockchains? We have talked about data integrity, authenticity and privacy. Well, quantum computers are not capable of breaking hash functions (with the right parameters). So an adversary will not be able to rewind what has already been recorded on a blockchain. Also, authenticity prior to quantum computers is still intact, since the adversary cannot travel back in time and forge a legitimate signature. Privacy, however, will be completely broken. With a quantum computer, the adversary can effectively break both ring signatures and zero knowledge proofs, thus, de-anonymizing every single piece of data. What makes this issue even more pressing is that our identity, although mathematically hidden, is already burned into blockchains. We will lose the privacy of those data that are already committed. Fortunately, we still have time to act now and migrate to quantum-safe cryptography.


