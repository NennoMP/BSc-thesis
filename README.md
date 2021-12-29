# BSc Computer Science thesis, case study of Yup: the social dApp of EOSIO blockchain.


## Introduction
Yup is the first social dApp of EOSIO blockchain and one of the most important social dApps in the entire blockchain ecosystem. It allows its users to rate/vote anything that has an url by simply using an extension in their browser. The users are then rewarded with the dApp's cryptocurrency, taking into consideration the quality of their votes and the affidability of the rated contents, for curating across the Web3.
  It is one of the first projects utilizing a cross-plaftorm and cross-blockchain approach; EOSIO blockchain is used for operating Yup's Smart Contract, because of its high scalabity and fast transactions, and Etheruem blockchain for Yup's liquidity pool (on Uniswap v2). This cross-chain approach is possible thanks to a Bridge mechanism that allows communication and interaction between the mentioned blockchains.
  
## What did I do
I developed multiple programs (in Python) for retrieving, by interfacing with the blockchain through API requests, storing, in JSON format so that the data could later be processed by other tools, and analyzing, by a socio-economic point of view, all the transactions/actions of the Yup's Smart Contract. I retrieved more than 23 million transactions (approx. 33GB JSON file size), from the beginning of its activity to the end of Feb 2020. Also, since Yup allows its users to register using their Twitter account and to interact with the most popular social networks (e.g. Twitter, Youtube, Reddit), I conducted further analysis using Twitter and Youtube API's in order to see the level of connection between relations (e.g. followers, people liking same contents) on Yup and others platforms
  
