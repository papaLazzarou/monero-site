---
layout: moneropedia
entry: "Block"
terms: ["block", "blocks"]
summary: "a container of transactions"
---

### The Basics

A block is a container of @transactions, with a new block being added to the @blockchain once every 60 seconds, on average.

Blocks also contain a special type of transaction, the @coinbase transaction, which add newly created Monero to the network.

Blocks are created through the process of @mining, and the @node that successfully mines the block then broadcasts it to each of the @nodes connected to it, who subsequently re-broadcast the block until the entire Monero network has received it.

Fake or bad blocks generally cannot be created, as @nodes that receive blocks always verify the @transactions they contain against a set of consensus rules that all nodes adhere to, including validating the cryptographic @signatures on each transaction.