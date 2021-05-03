This is a simple blockchain implementation in C++ for learning purposes. I used the following as starting points:

https://davenash.com/2017/10/build-a-blockchain-with-c

https://github.com/tko22/simple-blockchain

Have done basic unit testing in the main.cpp itself.

The goal was to understand what blockchain technology is and how the basics work.



## What does it do?

It will try to instantiate a blockchain with a genesis block and then loop till it mines and adds 9 more blocks to the blockchain.

## This project includes:
* Basic blockchain implementation (in-memory storage)
* Block mining with difficulty
* Multi-threaded block miners/nonce finder
* Block verification logic

External Libraries (included in source):

Zedwood.com SHA256 C++ library in zedwood 
