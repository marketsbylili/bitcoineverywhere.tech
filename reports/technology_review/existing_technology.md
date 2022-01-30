---
title: "Existing Technology"
---

We summarize below existing Bitcoin technology, how it is relevant for our target audience and offer suggestions for how it could be improved.

* Bitcoin Wallets
* Lightning Wallets
* Secure Chat Apps
* Full Nodes
* Onion Routing
* Coinjoin/Mixing'
* Transaction histories on all public blockchains are easily auditable. Coinjoining, or mixing, is a simple way for miners to protect their financial privacy by obscuring the history of their holdings. Sometimes referred to as “cleaning” by privacy advocates, the mixing process prevents blockchain data watchers from following where coins originated and accessing their full transaction history. Users should note that mixing is often used interchangeably with "tumbling" and "coinjoin." "Tumbling" is an older technique where users give up custody of their coins and hopefully receive coins with a different history. In this article, we will use the term "mixing" in reference to "coinjoin" transactions.
A coinjoin is a multi-party transaction where several senders contribute coins to a mix and receive the same amount of bitcoin to complete the transaction. After a mix has completed, a blockchain watcher cannot know which transaction output is linked to an input. Coinjoin transactions are non-custodial and do not require trust or handing over keys like tumbling.
For optimal privacy, consistent and multiple remixes are ideal. Why does this matter? One round of coinjoin breaks deterministic links (separates the coins from its history), but, remixes increase a user’s anonymity (anon) set. 
It is also possible to mix directly into cold storage. Please see the Sparrow guide linked above, or if you prefer using the full Samourai stack, please see this guide written by @Diverter_noKYC.
Coinjoining is not risk-free. Past transaction histories are not erased per se; only forward-looking privacy is achieved for mixed coins. Similarly, mixing does not undo a KYC event, meaning that an owner’s name is still recorded as belonging to past transaction history from when coins were used or purchased or spent. But mixing provides a sort of clean slate for users wishing to disconnect future use from past transaction histories. 
Centralized cryptocurrency exchanges also represent another barrier for using mixed coins. Most exchanges flag deposits made from external addresses with mixed transaction outputs that can occur during mixing. Transferring or selling coins through peer-to-peer markets or other KYC-free platforms, however, is rarely restricted. Setting aside some amount of non-mixed bitcoins is a good practice to have the option of using services that reject mixed coins if necessary.


* Off-grid Communication

### Summary