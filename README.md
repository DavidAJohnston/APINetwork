APINetwork
==========

API Network Protocol

=================================

vs0.1 (Basic Edition)

DavidJohnstonCEO (djohnstonec at gmail dot com)
Curtis Lacy

# Summary

We claim that APIcoin can provide a platform for developers to easily access APIs + IMAP.

* Will provide access to a wide variety of API's.
* Will provide access to IMAP.
* Will provide initial funds to incentizive developers to build software which implements the new protocol layers, and incentivize people to provide hosting of the APIcoin service.
* Will richly reward early adopters of the new protocol, in proportion to how successful it is.


# Assumptions

Our claims are built on the following assumptions in the API Network Protocol:


# Visualization of the APIcoin Token Tech Stack

The proposed protocol layers can be visualized as follows, with arrows representing users exchanging between currencies:

![Mastercoin Protocol Layers](https://raw.github.com/mastercoin-MSC/spec/master/images/layers.png) 


Note that all transfers of value are still stored in the normal bitcoin block chain, but higher layers of the protocol assign additional meaning to some transactions.

# Document History

1. Version 0.1

Previous versions of this document can be found at: 

# Operating on Top of the Mastercoin Design

The “Mastercoins” protocol layer between the existing bitcoin protocol and users’ currencies is intended to be a base upon which anyone can build their own currency. The software implementing Mastercoins will contain simple tools which will allow anyone to design and release their own currency with their own rules without doing any software development.

## The “APIcoin Initial Token Generation”

The APIcoin protocol uses the Mastercoin Protocol to create a user currency identifer. These tokens will be generated by the participants in the "API Address", a Bitcoin address starting January 15th.

Initial distribution of APIcoins will essentially be a effort to incentivize for developers to write the software which fully implements the protocol. The distribution is very simple, and will proceed as follows:

1. Anyone sending bitcoins to the "API Address" before February 15th, 2014 is recognized by the protocol as owning 100x that number of APIcoins. For instance, if I send 100 bitcoins to the "API Address" before February 15th, my bitcoin address owns 10,000 APIcoins after February 15th. 
2. Early buyers get additional Mastercoins. In order to encourage adoption momentum, buyers will get an additional 10% bonus APIcoin if they make their purchase a week before the deadline, 20% extra if they purchase two weeks early, and so on, including partial weeks. Thus, if I send 100 bitcoins to the exodus address 1.5 weeks before August 31st, the protocol recognizes my bitcoin address as owning 11,500 Mastercoins (10000 + 15% bonus).
3. Attempts to send funds to the Exodus Address on or after February 15st 2014 (as determined by bitcoin block chain records) will not be considered APIcoin purchases.


In the event that a purchase has multiple inputs, the input address contributing the most funds is recognized as owning the APIcoins.

Note that anyone who purchases Mastercoins also receives the same number of “Test Mastercoins” which will be used for testing new features before they are available for use in the Mastercoin protocol.


## Developer APIcoins (Dev API)

For every 1 APIcoin sold, an additional “Developer APIcoin” will also be created, which will be awarded to the API Address slowly over the following years. These delayed APIcoins will ensure that the community can incentivize developers to increase the value of APIcoin by completing the features desired by users. The reward will be structured so that the distributed bounty system receive 50% of the Dev APIcoins by one year after the initial sale, 75% by a year later, 87.5% by a year later, and so on:


## Transferring APIcoins

Say you want to transfer 1 APIcoin to another address. This is done through the Mastercoin client implimetations and its "Decentralized Exchange" feature.

Note that the amount to transfer is multiplied by 100,000,000 before it is stored, which allows for APIcoins to be sent with the same precision as bitcoins (eight decimal places).
