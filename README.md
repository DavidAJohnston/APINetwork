API Network
==========

API Network Protocol

=================================

Version 0.1 (Whitepaper Proposal Edition)

Curtis Lacy https://github.com/curtislacy

David Johnston https://github.com/DavidJohnstonCEO

## Summary

We claim that API Network can provide a platform for developers to easily access APIs + IMAP.

* Will provide access to a wide variety of both private and public API's.
* Will provide access to IMAP, Exchange, data normalization and natural language processing services in a federated manor.
* Will aquire initial backing as part of crowdsale to incentizive developers to build software which implements the API Network Protocol, and incentivize nodes to provide hosting of the API Network service.
* The API Network will operate using the "API token" to access its service.

## Technical Assumptions

Our claims are built on the following technical assumptions of technologies the API Network Protocol relies on for implimentation:
1. The Bitcoin Network can be used as a cryptographic ledger for the secure transfer of value and recording of records.
2. The Master Protocol can provide the issuance of digital tokens on top of the Bitcoin cryptographic ledger.
3. The Safe Network can provide secure decentralized storage of data for the caching of API information.
4. API Network Protocol can leverage digital marketplace tools such as decentralized escrow, reputation, identity, and arbitration to operate an efficent Federated marketplace for pulbic APIs.

## Visualization of the APIcoin Token Tech Stack

The proposed protocol layers of Bitcoin, Master Protocol, and the API Network can be visualized as follows, with arrows representing users exchanging between currencies:

![Mastercoin Protocol Layers](https://raw.github.com/mastercoin-MSC/spec/master/images/layers.png) 

Note that all transfers of value using the Master Protocol are still stored in the normal bitcoin block chain, but higher layers of the protocol assign additional meaning to some transactions.

# Document History

1. Version 0.1
This version seeks to describe the features that will be implimented after the API Network crowdsale.

## Features of the API Network

1. Private API Marketplace: A node may join the API Network and publish a private API that it wants to provide calls for. The node will accept and price the calls to its API in API Tokens. This will establish a market place with nodes providing a variety of API calls. The use of the SAFE Network for publishing data and that data's access will generate SAFE coins at the Bitcoin address provided by the API publisher.

2. Storage of Cached API Data: The API Network will use SAFE Network in the backend to store the cached API data for users. This will be accomplished through the conversion of API Tokens to SAFE coins to purchase storage space for the user. 

3. API Billing Module: The API Network will require sending of API tokens to the API before the API services are provided, and the system will use AnArk.it for the escrow and holding of the API tokens for its billing module. That way the handling of the API tokens can be done in a completely decentralized way where neither the user nor the API publisher can access the API tokens until such time as the promised action is preformed to the satisfaction of both parties.

4. Data Normalization: The API Network contains libraries and tools for the normalizatin of data. This tool set is open source and available to all users of the API Network system and will be maintined as part of the core implimentation of the API Network Protocol. 

5. IMAP Intergration: The API Network contains libraries and tools for the intergration of IMAP email systems. This tool set is open source and available to all users of the API Network system and will be maintined as part of the core implimentation of the API Network Protocol. 

6. Exchange Intergration: The API Network contains libraries and tools for the intergration of exchange email systems. This tool set is open source and available to all users of the API Network system and will be maintined as part of the core implimentation of the API Network Protocol. 

7. Single Developer Interface: The API Network contains libraries and tools for developers to interact with multiple API's through a single interface. This tool set is open source and available to all users of the API Network system and will be maintined as part of the core implimentation of the API Network Protocol.

8. Natural Language Processing Tools:  The API Network contains libraries and tools for the processing and indexing of natural language. This tool set is open source and available to all users of the API Network system and will be maintined as part of the core implimentation of the API Network Protocol.

9. Public API Marketplace: The API Network will provide a marketplace for public APIs (Gmail, Facebook, Twitter and so forth) to be accessed through a Federated Network of API hosting providers. This marketplace of public API's will provide access to reputation and identity systems (anark.it and onename.io for example) to allow users to pick the API call provider of their choice. The marketplace for public API's will leverage the API Network opensource data normalization, interface and natural language process tools. 

## Operating on Top of the Mastercoin Design

The “Master Protocol" layer exists between the existing bitcoin protocol and users’ currencies. The software implementing the Master Protocol contains simple tools which will allow anyone to design and release their own currency with their own rules without doing any software development.

## The “API Token Generation”

The API Network uses the Mastercoin Protocol to create a user currency identifer. These tokens will be generated by the participants in the "API Address", a Bitcoin address starting June 15th 2014.

Initial distribution of API Tokens will essentially be a effort to incentivize for developers to write the software which fully implements the protocol. The distribution is very simple, and will proceed as follows:

1. Anyone sending bitcoins to the "API Address" before July 15th, 2014 is recognized by the protocol as owning 100x that number of API Tokens. For instance, if the user sends 100 bitcoins to the "API Address" before July 15th, their bitcoin address owns 10,000 APIcoins after July 15th. 
2. Early buyers get additional API Tokens. In order to encourage adoption momentum, buyers will get an additional 10% bonus API Tokens if they make their purchase a week before the deadline, 20% extra if they purchase two weeks early, and so on, including partial weeks. Thus, if I send 100 bitcoins to the "API Address" 1.5 weeks before the 15th of July 2014, the protocol recognizes my bitcoin address as owning 11,500 API Tokens (10000 + 15% bonus).
3. Attempts to send funds to the API "Address" on or after midnight (central time) July 15st 2014 (as determined by bitcoin block chain records) will not be considered API Tokens purchases and shall be sent back.

In the event that a purchase has multiple inputs, the input address contributing the most funds is recognized as owning the API Tokens.

Note that anyone who purchases API Tokens also receive the ability to test new features before they are available for use in the API Network Protocol.


## Developer API Tokens (Dev Tokens)

For every 4 API Token sold, an additional “Developer API Tokens” will also be created, which will be awarded to the API Address slowly over the following years. These delayed API Tokens will ensure that the community can incentivize developers to increase the value of API Token by completing the features desired by users. The reward will be structured so that the distributed bounty system receive 50% of the Dev API Tokens by one year after the initial sale, 75% by a year later, 87.5% by a year later, and so on:

SAFE coins generated by the use of API's published on the API Network will be sent to the API Network developer pool purchase API coins on the Decentralized Exchange and hold them for release to contributors to the API Network open source code.

## Transferring APIcoins

Say you want to transfer 1 API Token to another address. This is done through the Master Protocol client implimetations.

Note that the amount to transfer is multiplied by 100,000,000 before it is stored, which allows for API Tokens to be sent with the same precision as bitcoins (eight decimal places).

