---
layout: page
permalink: /program
---

## Program
All times in Eastern Time. The program is conducted online on Zoom (link will be shared soon).

| 3rd April           |              |
| ------------------- | ------------ |
| 10.00 AM - 10.15 AM | Introduction |
| 10.15 AM - 10.45 AM | [Natacha Crooks, UC Berkeley](#natacha-crooks) |
| 10.45 AM - 11.15 AM | [Heidi Howard, Microsoft Research](#heidi-howard) |
| 11.15 AM - 11.45 AM | [Mic Bowman, Intel](#mic-bowman) |
| 11.45 AM - Noon | Break | 
| Noon - 12.30 PM | Panel |
| 12.30 PM - 1.00 PM | [Matt Green, Johns Hopkins](#matt-green) |
| 1.00 PM - 1.30 PM | [Jonathan Passerat-Palmbach, Flashbots](#jonathan-passerat-palmbach) | 
<br>
| 4th April           |              |
| ------------------- | ------------ |
| 10.05 AM - 10.15 AM | Introduction |
| 10.15 AM - 10.45 AM | [Nick Hynes, Oasis Labs](#nick-hynes) |
| 10.45 AM - 11.15 AM | [Andrew Miller, UIUC](#andrew-miller) |
| 11.15 AM - 11.45 AM | Panel |
| 11.45 AM - Noon | Break | 
| Noon - 12.30 PM | [Ittay Eyal, Technion](#ittay-eyal) |
| 12.30 PM - 1.00 PM | [Guy Zyskind, Secret Network](#guy-zyskind) |

<br>

### Natacha Crooks

### Heidi Howard
<ul>
<h4> Confidential Consortium Framework: Building Secure Multiparty Applications in the Cloud (Without Handing Over the Keys to the Kingdom!) </h4>
</ul>
<ul>
  <b>Abstract.</b> In the pre-cloud era, computer systems were operated by the organizations which depended upon them. This on-premises approach gave organizations great power over their systems, however, “with great power comes great responsibility” and organizations were left with the ongoing burden of deploying and managing their own infrastructure. Today, Cloud computing has removed much of the responsibility of deploying systems, however, it has also removed much of the power that organizations once had. Organizations must place their trust in the cloud to secure the confidentiality and integrity of their data.
</ul>

<ul>
In this talk, I'll consider whether it is possible to regain control over data in the cloud (great power with none of the responsibility) and even enable multiple untrusted parties to compute together on untrusted infrastructure. I’ll introduce the Confidential Consortium Framework (aka CCF), an open-source framework for building a new category of secure multiparty applications with confidentiality, integrity-protection, and high availability. CCF utilizes hardware-based trusted execution environments for remotely verifiable confidentiality and code integrity, backed by an auditable and immutable distributed ledger for data integrity and high availability. CCF even enables application developers to bring both their own application logic and a custom multi-party governance model, in the form of a programmable constitution. By the conclusion of this talk, I hope to have convinced you that distributing systems does not necessarily mean distributing trust in the era of trusted execution in the cloud. You can learn more about CCF today at: https://ccf.dev/
</ul>

<ul>
  <b>Bio.</b> Heidi is a Senior Researcher in the Confidential Computing group at Microsoft Research Cambridge. Her research sits at the intersection between the theory and practice of distributed computing, with a focus on developing resilient and trustworthy distributed computer systems. Previously, she was a Research Fellow in Computer Science at Cambridge University’s Trinity Hall, an Affiliated/Visiting Researcher at VMware Research, and an Affiliated Lecturer at Cambridge University’s Department of Computer Science and Technology. She received her Ph.D. from Cambridge University in 2019 for her research on Distributed Consensus. She is best known for her work on the Paxos algorithm, and in particular, the invention of Flexible Paxos.
</ul>

### Mic Bowman
<ul>
<h4> Building Decentralized Trust with a Trusted Execution Environment</h4>
  </ul>

<ul>
<b>Abstract.</b> The promise of hardware-based Trusted Execution Environments (TEEs) is a place where compute can happen beyond the observation and control of hosting parties. For multiparty applications the TEE can, in theory, become the trusted third party that arbitrates shared "truth". And TEE's can provide this without the redundancy and replication required by software-only alternatives such as distributed consensus protocols. However, there are many examples show that no security technology is completely immune to attack including HW-based TEEs. If TEEs aren't "perfect", what then is their appropriate role in multi-party computations? This talk will go through some of the lessons we've learned about building robust decentralized, multi-party applications with TEEs and how to use a TEE to reduce the risk of successful attacks.
  </ul>

<ul>
<b>Bio.</b> Mic Bowman is a senior principal engineer in Intel Labs and leads the decentralized computing research group. Mic has spent over 20 years working on large-scale databases and distributed systems. Among other roles he served as a member of the Hyperledger Technical Steering Committee for several years contributing to various aspects of architecture definition and evaluation of technologies for privacy and confidentiality. He is currently working on methods for improving the security, scalability, and privacy of distributed ledgers. He received his PhD in Computer Science from the University of Arizona.
  </ul>

### Matt Green

<ul>
<b>Ask not what secure hardware can do for ledgers, but what ledgers can do for secure hardware</b>
</ul>

<ul>
<b>Abstract.</b> Over the past several years, a number of proposals have proposed to use the power of Trusted Execution Environments (TEEs) to provide new capabilities to consensus networks and blockchains. In this talk we will address the opposite direction: how can blockchains be used to enhance the power of TEEs and related technologies? Our answer will introduce the concept of a “proof of publication ledger” and will demonstrate the fundamental capabilities that these systems add to TEE-based systems, including state synchronization, one-time execution, and secure data publication. We further review some recent results from the theoretical cryptography community on the interaction of ledgers and cryptographic obfuscation techniques, as a preview of what may be possible in the future.
</ul>

<ul>
<b>Bio.</b> Matthew D. Green is an Associate Professor at the Johns Hopkins University Information Security Institute. He has worked on privacy-preserving technologies and new systems for verifiable execution, and is a co-designer of the Zexe and Zcash systems.
</ul>

### Jonathan Passerat-Palmbach
<ul>
<b>Privacy x MEV: mitigation, collaboration, decentralisation</b>
</ul>

<ul>
<b>Abstract.</b> This presentation aims to discuss the utilisation of trusted execution environments (TEEs) and privacy enhancing technologies to mitigate the risks of Maximal Extractable Value (MEV). We will start by introducing MEV, highlighting the potential risks it poses to blockchains consensus. Then we will see how Flashbots proposed to handle MEV, via a suite of hosted services spanning PoW and now PoS Ethereum. Finally, we will discuss the research directions Flashbots is pursuing to address MEV through the use of TEEs, and our plans to combine them with privacy-enhancing technologies. This presentation aims to provide a comprehensive understanding of the challenges posed by MEV and give the directions we are currently following so that more collaborators can join us on this open research journey.
</ul>

<ul>
  <b>Bio.</b> Jonathan is a senior research scientist at <a href="https://www.flashbots.net/">Flashbots</a>. He is exploring the application of Privacy Enhancing Technologies to solve hard problems such as decentralised collaborative learning and Maximum Extractable Value (MEV) in blockchains. He has grown a strong expertise in Secure Computing (Trusted Execution Environments - TEEs, FHE, ...), Federated Learning and Verifiable Computing (TEEs, Zero-Knowledge Proofs, ...). Jonathan is also a research fellow at Imperial College London (<a href="https://biomedia.doc.ic.ac.uk">BioMedIA</a>) and City, University of London (<a href="https://cit-ai.net">CitAI</a>) where he co-supervises research students on the topics Privacy-Preserving Machine Learning and Federated Learning. He formerly lead the R&D arm of ConsenSys / <a href="https://equideum.health/">Equideum Health</a>, where the team focuses on bringing together privacy-preserving machine learning and blockchains to build a new generation of healthcare systems.
</ul>

### Nick Hynes
<ul>
<b>A Privacy Layer for Web3 - Discover how to unlock the potential of Web3 with the Oasis Privacy Layer</b>
</ul>

<ul>
<b>Abstract.</b> Come learn about the value of privacy in Web3 and how easy it is to add it to your dApp using the Oasis Privacy Layer, an EVM-compatible privacy solution powered by TEE where state and transactions are encrypted and visible only to the user and the contract. The talk explores the potential of the Oasis Privacy Layer, powered by Sapphire, for adding confidentiality to dApps on any EVM network. Nick will further demonstrate how this technology can help developers build privacy-focused applications on the decentralized web, discuss the challenges and opportunities in blockchain privacy and how to add confidentiality to dApps built on EVM networks within minutes.
</ul>

<ul>
<b>Bio.</b> Nick Hynes, the Tech Lead at Oasis is working on building the privacy layer for Web3 on Sapphire, the first ever confidential EVM, along with various blockchain applications. At Oasis, Nick has worked on projects such as building the first WebAssembly blockchain runtime that allows executing confidential contracts, created an SDK for authoring them in Rust and TS, and designed and built Parcel, a private data sharing and computation platform; deployed to a wide range of beta customers including Mollie, ADP, Headspace, and Frontend. While a PhD student at Berkeley, Nick worked on secure and private AI. He also holds a M.Eng degree from MIT in EECS with a focus on AI.
</ul>

### Andrew Miller
<ul>
  <b><a href="https://eprint.iacr.org/2023/378"> TEE-based smart contracts: pitfalls and challenges</a></b>
  </ul>
  
<ul>
<b>Abstract.</b> I'll discuss design challenges and opportunities around TEE-based smart contracts, especially based on our recent experience of coordinated vulnerability disclosures involving access patterns and replay attacks. These are a powerful tool but not a silver bullet, and a bunch of technical debt must be repaid in order to build a secure system that relies on them.
</ul>

<ul>
<b>Bio.</b> Andrew is an Assistant Professor at the University of Illinois, Urbana-Champaign, in Electrical and Computer Engineering and affiliate in Computer Science. He is also an Associate Director of the Initiative for Cryptocurrencies and Contracts (IC3) and a board member of the Zcash Foundation. He received his Ph.D. from the University of Maryland Cybersecurity Center.
</ul>


### Ittay Eyal

<ul>
<b>Teechain: A Secure Payment Network with Asynchronous Blockchain Access</b>
</ul>

<ul>
<b>Abstract.</b> We present Teechain, the first layer-two payment network that executes off-chain transactions asynchronously with respect to the underlying blockchain. To prevent parties from misbehaving, Teechain uses treasuries, protected by hardware trusted execution environments (TEEs), to establish off-chain payment channels between parties. Treasuries maintain collateral funds and can exchange transactions efficiently and securely, without interacting with the underlying blockchain. To mitigate against treasury failures and to avoid having to trust all TEEs, Teechain replicates the state of treasuries using committee chains, a new variant of chain replication with threshold secret sharing. Teechain achieves at least a 33x higher transaction throughput than the state-of-the-art Lightning payment network. A 30-machine Teechain deployment can handle over 1 million Bitcoin transactions per second.Joint work with Joshua Lind, Oded Naor, Florian Kelbert, Emin Gun Sirer, and Peter Pietzuch. This result was first published in SOSP'19.
</ul>

<ul>
<b>Bio.</b> Ittay Eyal is an associate prof. in the Electrical and Computer Engineering Faculty at the Technion and an associate director at the Initiative for Cryptocurrencies and Contracts (IC3). Eyal completed his PhD at the Technion, followed by a post-doctorate at Cornell University. Eyal was awarded a 2018 Alon Scholarship and a 2022 Krill Prize. His research focuses on performance and security in decentralized systems. 
</ul>

### Guy Zyskind
