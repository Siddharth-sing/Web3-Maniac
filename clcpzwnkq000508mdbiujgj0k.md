# 5 key components of blockchain every developer should know

If you are interested in Ethereum Blockchain Development, please check out the roadmap I discussed [here](https://dev.to/siddharthsing/roadmap-to-blockchain-development-on4).

In this article, I will be discussing five fundamental concepts of blockchain that every developer should know whether they want to enter the web3 environment or not. Also, this article series on dev.to will be a complete guide to Ethereum Blockchain Development, so stay tuned.

![Let's Started gif](https://cdn.hashnode.com/res/hashnode/image/upload/v1673339266274/lMLHUwacd.gif align="left")

## Some keywords to understand the article :

* **Public Key** - It is a cryptographic key (a long sequence of hexadecimal numbers ) that can be obtained and used by anyone to encrypt messages or transactions intended for a particular recipient, such that the encrypted messages can be deciphered only by using a second key that is known only to the recipient (the private key ).
    
* **Private Key** - As pointed out above a private key is a decipherer or a decoder for a message or transaction encrypted by the corresponding public key. The private key must not be shared with anyone as it is capable of making transactions from your address.
    
* **Consensus Mechanism** - A consensus mechanism refers to any number of methodologies used to achieve agreement, trust, and security across a decentralized computer network. In blockchains and cryptocurrencies, proof-of-work (PoW) and proof-of-stake (PoS) are two of the most prevalent consensus mechanisms through which blockchains sync every node present with the same data.
    

## 1\. Anonymity

So, it's true that Blockchains like Ethereum and Bitcoin are transparent, in other words, the history of every BTC, for instance, can be tracked from the block where it was mined to the wallet in which it is currently stored. Similarly, the history of transactions for all addresses can be tracked, as well, since addresses are identified by public keys, and these are visible to everyone.

Still, blockchain maintains anonymity somehow :

### Pseudonym or pseudonymity

Pseudonym, which means a name used by somebody, instead of his/her real name. Blockchain does the same, instead of taking your original name like the traditional banking systems, Blockchain transacts through your address (public key). For example, your real name can be Mike but in the Blockchain environment, you will be identified as " 1ExAmpLe0FaBiTco1NAdDr3sSV5tsGaMF6hd " or something else, something much longer.

![vs](https://cdn.hashnode.com/res/hashnode/image/upload/v1673339268162/1cYPynRa9.png align="left")

The above image shows how the traditional banking system exposes the users' name, address, and even contact number, whereas blockchain transactions transact using an alias that is a public key (address of the wallet).

Blockchain is powerful, hence just hiding our name won't make us safe in this very vast environment because with great powers comes greater threat. **Check out this 5 minutes Youtube video to understand Blockchains Anonymity**

{% embed https://www.youtube.com/watch?v=4pKBvJEk6Nc %}

## 2\. Decentralization

Nowadays we often hear phrases like **decentralization is the king**. So, what does it mean, and what is decentralization?

* **Decentralization** is the transfer of control and decision-making from a centralized entity (individual, organization, government, or group thereof) to a distributed network.
    

To understand it clearly, assume you made a transaction with your friend, and your friend received it. Now Here, the transaction happens between you and your friend, but the knowledge of the transaction is available to four entities, you, the friend, the banks involved (yours and your friend's), and the payment network processor (VISA, MasterCard, etc.).

The payment flow goes something like this (see the image below). In this traditional banking system, say you sent a request to your bank 'A' to send $500 to your friend, now the bank needs to verify you and your friend both, but let's say your friend's account is in bank 'B', then bank 'A' is unable to verify the details of your friend because banks don't share customer information (due to competition). Here come Payment Network Processors (VISA, MasterCard, etc.), every bank sells all their customer's data to these companies and they verify the users on behalf of the banks.

![Decentralization](https://cdn.hashnode.com/res/hashnode/image/upload/v1673339270140/Z9hBv7Tlf.png align="left")

Thatswhy decentralization is king, in a decentralized system, like cryptocurrency (BTC, ETH, DogeCoin, etc. ), if a user sends cryptocurrency to their friend or anyone, only the sender and receiver will know about the transaction. The image below compares Centralized Finance (CeFi) and Decentralised Finance (Defi).

![Decentralization](https://cdn.hashnode.com/res/hashnode/image/upload/v1673339271750/n_KJ4gioYn.jpeg align="left")

## 3\. Fault Tolerance

A decentralized blockchain network looks something like this (see the image below). Several nodes (or blocks) throughout the world are connected without any centralized authorities regulation. All the nodes are connected through a Consensus agreement, therefore each node is synchronized and has the same transaction ledger throughout the blockchain network. Since all nodes have the same data present in them, if one or two nodes are compromised or have a threat, the system still does not become faulty. Those faulty nodes will be removed from the network and the blockchain goes on.

![Fault tolerance](https://cdn.hashnode.com/res/hashnode/image/upload/v1673339273717/7EsYztDN1.gif align="left")

## 4\. Immutability

Immutability is a much-coined term in the web3 community. Blockchain is an immutable database, and you cannot manipulate data that are already present in the blockchain. How come? For that let's see how hash codes generate and what a block structure looks like.

**Hash Code** - Hash codes are long hexadecimal sequences that are generated through various algorithms like SHA-1. Hash codes can vary greatly by just changing a letter of your name. For example, **DEV** can be hashed as "**FA489B5C2003**", but, **DAV** will become "**A8DC567B89E**". Hence hackers trying to manipulate transactions in the blockchain immediately causes the change of hashcodes and the system indicates the node is faulty.

> See the monkey gif below for the reference of how broadly a hashcode changes by changing a few things.

![monkey](https://cdn.hashnode.com/res/hashnode/image/upload/v1673339275630/og36gX_bFr.gif align="left")

**Block Structure** - Each block in a blockchain contains two long hashcodes. One is the hash of the block itself and the other is the previous block hash (see the image below). The previous block's hash is used to connect both the blocks together similar to a linked list. Now, suppose any hacker changes the transaction detail in any one block, its hashcode will be changed completely causing the break of the chain from the faulty node.

![ledger](https://cdn.hashnode.com/res/hashnode/image/upload/v1673339277385/iNJheUB9z.jpeg align="left")

That is why it is so damn difficult to update a blockchain node because if anyone tries to update one node all the consecutive nodes should be updated simultaneously and hence blockchain is nearly immutable.

## 5\. Trustless

Trustless is the quality of decentralization. Blockchain network is called trustless not because you can't trust it but because you don't have to trust any third party for your transactions. The transactions in the crypto environment are completely peer-to-peer-based (P2P) transactions where no centralized authorities (government, banks, etc.) are involved. Hence blockchain is called a trustless environment. Although no system can be completely trustless, at some point we have to trust any organization but in blockchain that anyone would be a code instead of a person.

## Writer's Support

* If you find the article useful, show some love ❤️ by following me on LinkedIn, GitHub, Instagram, Twitter, or everywhere 🤩.
 <p>
<a href="https://twitter.com/SidharthSing20">
  <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white">
  </a>
  <a href="https://www.linkedin.com/in/siddharth-singh-baghel-912866190/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
  </a>
  <a href="https://github.com/Siddharth-sing">
  <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white">
  </a>
  <a href="https://dev.to/siddharthsing">
  <img src="https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white">
  </a>
<a href="https://www.instagram.com/i_m_siddharth.singh/">
  <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white">
  </a>
<p>