---
layout: page
permalink: /program
---

## Program
The program is conducted online on Zoom.


| 15th August (eastern time)         |              |
| ------------------- | ------------ |
| 10.00 AM - 10.10 AM | Introduction |
| 10.10 AM - 10.45 AM | [Justin Drake, Ethereum Foundation](#justin-drake) |
| 10.45 AM - 11.20 AM | [Sreeram Kannan, EigenLayer](#sreeram-kannan) |
| 11.20 AM - 12.00 PM | Panel | 
| 12.00 PM - 12.20 PM | Break | 
| 12.20 PM - 12.55 PM | [Matheus V. X. Ferreira, Harvard University](#matheus-ferreira) |
| 12.55 PM - 01.30 PM | [Elaine Shi, CMU](#elaine-shi) |


<br>

### Matheus Ferreira

<ul>
  <h4> Algorithm Design under the Credibility Lenses </h4>
  </ul>
<ul>
  <b>Abstract.</b> Imagine you are buying something online, like on eBay. You might use an auction, which is a way of finding the best price for an item by letting people bid on it. But how do you know that the auction is fair? What if the person who runs the auction is also bidding on the item with a fake name to make you pay more or get less? This problem happens on many online platforms, and it is hard to detect or prevent. This problem is even more prevalent in blockchain applications like decentralized exchanges because agents use pseudonymous identities. As a result, one cannot rely on agents' reputations to avoid predatory behavior. In this talk, I will overview the challenges of designing online platforms that are trustworthy by exploring the design of credible mechanisms. By taking credibility as a first-order constraint, the algorithm designer proposes to follow a particular algorithm but later can deviate. An algorithm is credible if, after promising to follow such an algorithm, the algorithm designer does not have the incentive to deviate from its promised specification. As a proof of concept, I will show how the credibility lenses allow us to design decentralized exchanges and online auctions that can be trusted by users under highly adversarial environments.

  </ul>

  <ul>
  <b>Bio.</b> Matheus Venturyne Xavier Ferreira is a Postdoctoral Fellow in Computer Science at Harvard John A. Paulson School of Engineering and Applied Sciences, and starting in Summer 2024, he will be an Assistant Professor of Computer Science at the University of Virginia. He earned his Ph.D. (2022) and MA (2018) in Computer Science from Princeton University and his BS in Computer Engineering (2016) from the Federal University of Itajubá. His research interests include AI, Algorithmic Economics, and Security. He applies artificial intelligence, optimization, and theoretical computer science tools to create secure, transparent, and auditable platforms. Matheus hails from Itabira, the Brazilian capital of poetry.
</ul>
    
### Justin Drake
<ul>
<h4> MEV Burn </h4>
</ul>
<ul>
  <b>Abstract.</b> Justin will talk about EIP-1559 for MEV.
</ul>

<ul>
  <b>Bio.</b> Justin is a researcher at Ethereum Foundation.
</ul>

### Sreeram Kannan
<ul>
<h4> StakeSure: Proof of Stake Mechanisms with Strong Cryptoeconomic Safety</h4>
  </ul>

<ul>
<b>Abstract.</b> As of June 15, 2023, Ethererum, which is a Proof-of-Stake (PoS) blockchain has around 410 Billion USD in total assets on chain but has only ~33 Billion USD worth of ETH staked in securing the underlying consensus of the chain \cite{ultrasound}. A preliminary analysis might suggest that as the amount staked is far less (11x less) than the value secured, the Ethereum blockchain is insecure and “over-leveraged” in a purely cryptoeconomic sense. In this work, we investigate how Ethereum, or, more generally, any PoS blockchain can be made secure despite this apparent imbalance. Towards that end, we attempt to formalize a model for analyzing the cryptoeconomic safety of PoS blockchain, which separately analyzes the cost-of-corruption, the cost incurred by an attacker, and the profit-from-corruption, the profit gained by an attacker. We derive sharper bounds on profit-from-corruption, as well as new confirmation rules that significantly decrease this upper-bound. Finally, we present a new “insurance” mechanism, STAKESURE, for allocating the slashed funds in a PoS system, that has several highly desirable properties: solving common information problem in existing blockchains, creating a mechanism for provably safe bridging, and providing the first sharp solution for automatically adjusting how much economic security is sufficient in a PoS system. Finally, we show that the system satisfies a notion of strong cryptoeconomic safety, which guarantees that no honest transactor ever loses money, and creates a closed system of Karma, which not only ensures that the attacker suffers a loss of funds but also that the harmed parties are sufficiently compensated.
  </ul>

<ul>
<b>Bio.</b> Sreeram Kannan is founder of EigenLayer, a project working on programmable staking, and till recently, was Associate Professor at UW, running the UW blockchain lab and the Information Theory Lab. His research interests are in blockchain, AI and computational genomics. 
  </ul>

### Elaine Shi

<ul>
<b>Decentralized Mechanism Design</b>
</ul>

<ul>
<b>Abstract.</b> In transaction fee mechanism design, users bid to get their transactions confirmed in the block. Classical auctions completely fail in such a decentralized environment where even the auctioneer (i.e., miners) can be a strategic player. Further, the miners can collude with a subset of the users, e.g., facilitated by real-world platforms like Flashbots. A line of works have attempted to devise a "dream" transaction fee mechanism but all have failed. In this talk, I will first show that this is not a coincidence --- in fact, there is a fundamental mathematical barrier towards achieving a "dream" transaction fee mechanism. Then, I will explain how to overcome impossibilities with the help of cryptography, leading to practical mechanisms that achieve good social welfare and revenue.
</ul>
