# Oracles

### What is an oracle <a href="#what-is-an-oracle" id="what-is-an-oracle"></a>

An oracle, in this context, is a bridge between the closed system of a blockchain and the rest of the world. They provide external data on-chain, typically codified through a smart contract.

Here is a video explaining oracles:\


{% embed url="https://www.youtube.com/watch?t=11s&v=ZJfkNzyO7-U" %}

### Why are they needed? <a href="#why-are-they-needed" id="why-are-they-needed"></a>

Oracles are needed for two reasons.

First, blockchains are closed systems. They do not have the capacity to reach out of their own network. This is on purpose, because it keeps the process of reaching a [consensus](../../concepts/computational-utilities/consensus-mechanism.md) feasible for modern computers. Thus, the question arises: "Do we ever need to access data that is not generated by the blockchain?"

Second, blockchains are reliable systems. A well-designed and well-run blockchain is not as easily hacked as a standard API hosted on a cloud server. If your users depend on some data that you produce, then you could use an Oracle to store it. This means that the same guarantees exist for your API data as exist for any given data on the blockchain.

This concept applies to data from markets, sensors, usage statistics, and anything that you would want to codify and make accessible to the audience of the blockchain that you use.

### Usage <a href="#usage" id="usage"></a>

Using services like [Band](https://bandprotocol.com/data-provider), you can reference real-world, aggregated data on-chain. You can reference this data both in any on-chain smart contracts that you build or any off-chain systems that you build as well.

### Oracle services <a href="#other-services" id="other-services"></a>

[Band Protocol](https://docs.bandchain.org)

### Further reading <a href="#further-reading" id="further-reading"></a>

#### Articles

[What is a Blockchain Oracle?](https://betterprogramming.pub/what-is-a-blockchain-oracle-f5ccab8dbd72)

[Why can't smart contracts make API calls?](https://ethereum.stackexchange.com/questions/301/why-cant-contracts-make-api-calls)

#### Videos

[Oracles and the Expansion of Blockchain Utility](https://youtu.be/BVUZpWa8vpw)&#x20;