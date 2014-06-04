API Network
==========

API Network Protocol

=================================

Version 0.1 (Whitepaper Proposal Edition)

Curtis Lacy https://github.com/curtislacy

David Johnston https://github.com/DavidJohnstonCEO

## Summary

We claim that API Network will 

* A. provide a platform for developers to easily access multiple APIs + IMAP.
* B. provide access to a wide variety of both private and public API's.
* c. provide access to the private and public API's in a federated manner for data that is technically easy to host and index, such as IMAP and Exchange information. 
* D. aquire initial backing as part of crowdsale to incentizive developers to build the API Network Protocol's software.
* E. operate using the "APICoin" to grant access its service.
* F. compensate and incentivize nodes that are providing the API Network service in "APICoins"

## Technical Assumptions

Our claims are built on the following technical assumptions of technologies the API Network Protocol relies on for implimentation:
* A. The Bitcoin Network can be used as a cryptographic ledger for the secure transfer of value and recording.
* B. The Master Protocol can provide the issuance of digital and unique tokens on top of the Bitcoin cryptographic ledger.
* C. The Safe Network can provide secure decentralized storage of data for the caching of API information.
* D. API Network Protocol can host and manage Bitcoin wallets in an automated manner as indicated by users.
* D. API Network Protocol can leverage digital marketplace tools such as decentralized escrow, reputation, identity, and arbitration to operate an efficent Federated marketplace for pulbic APIs.

## Visualization of the APIcoin Token Tech Stack

The proposed protocol layers of Bitcoin, Master Protocol, and the API Network can be visualized as follows, with arrows representing users exchanging between currencies:

![Mastercoin Protocol Layers](https://raw.github.com/mastercoin-MSC/spec/master/images/layers.png) 

Note that all transfers of value using the Master Protocol are still stored in the normal bitcoin block chain, but the protocol assigns, stores and interprates additional meaning to some transactions utilizing the feature of embedded metadata. See Master Protocol for more additional information on user issued currencies and hosting crowdsales.

# Document History

* Version 0.1
This version seeks to describe the features that will be implimented after the API Network crowdsale.

## Features of the API Network

1. Private API Marketplace: A node may join the API Network and publish a private API that it will provide calls for. The node will accept and price the calls to its API in API Tokens. This will establish a link between the value of the service and that of the tokens. While the demand for the service will reflect in the demand for the token, the market place of nodes opertaing to perform a variety of API calls will be competing with each other thus rendering the service cheaper to perform. The competing supply and the competing demand will give rise to the dynamic emergent market place.

2. The use of the SAFE Network: When the API Publisher stores information on the SAFE Network, the SAFE protocol will issue tokens to the Bitcoin address provided by the API publisher, to enable sustained storage and recall.

3. Storage of Cached API Data: The API Network will use SAFE Network in the back-end to store the cached API data for users. This will be accomplished through the conversion of API Tokens to SAFE coins to purchase storage space for the user in the decentralized exchange.

4. API Billing Module: The API Network will require sending of API tokens before the API services are provided, and the system will use AnArk.it for the escrow and holding of the API tokens for its billing module. That way the handling of the API tokens can be done in a completely decentralized manner where neither the user nor the API publisher will be able to access the API tokens until the promised action is preformed to the satisfaction of both parties.

5. Data Normalization: The API Network contains libraries and tools for the normalizatin of data. This tool set is open-source, available to all users of the API Network system, and will be maintined as part of the core implimentation of the API Network Protocol. 

6. IMAP Intergration: The API Network contains libraries and tools for the intergration of IMAP email systems. This tool set is open-source and available to all users of the API Network system and will be maintined as part of the core implimentation of the API Network Protocol. 

6. Exchange Intergration: The API Network contains libraries and tools for the intergration of exchange email systems. This tool set is open-source and available to all users of the API Network system and will be maintined as part of the core implimentation of the API Network Protocol. 

7. Single Developer Interface: The API Network contains libraries and tools for developers to interact with multiple API's through a single interface. This tool set is open-source and available to all users of the API Network system and will be maintined as part of the core implimentation of the API Network Protocol.

8. Natural Language Processing Tools:  The API Network contains libraries and tools for the processing and indexing of natural language. This tool set is open source and available to all users of the API Network system and will be maintined as part of the core implimentation of the API Network Protocol.

9. Public API Marketplace: The API Network will provide a marketplace for public APIs (Gmail, Facebook, Twitter and so forth) to be accessed through a Federated Network of API hosting providers. This marketplace of public API's will provide access to reputation and identity systems (anark.it and onename.io for example) to allow users to pick the API call provider of their choice. The marketplace for public API's will leverage the API Network opensource data normalization, interface and natural language process tools. 

## Operating on Top of the Mastercoin Design

The “Master Protocol" layer exists between the existing bitcoin protocol and user-issued currencies. The software implementing the Master Protocol contains simple tools which allows anyone to design and release their own currency with their own rules without doing any software development.

## Total Distribution of APIcoins

Crowdsale APIcoins 200,000 (20%)
Node Incentive APIcoins 200,000 (20%)
Developer APIcoins 300,000 (30%)
Open Sourcing APIcoins 300,000 (30%)

Total APIcoins that will ever exist 1,000,000

## The Crowdsale “APICoin Generation”

The API Network uses the Master Protocol to create a user currency identifer. These tokens are generated by the participants in the "API Address", a Bitcoin address starting June 15th 2014. The generation will continue until the end of the 'crowdsale' event until the target amount of funding is committed or the ending date is reached.

Initial distribution of APICoins will essentially be a effort to incentivize developers to write the software which fully implements the protocol. The issuance of tokens will proceed as the following simple steps:

1. A dutch style auction sale of APIcoins will begin June 11th and a total of 2,000 APIcoins will be sold each day for a 7 day period. The 2,000 APIcoins generated during each day will be distributed in proportion to the bitcoin addresses that sent the BTC. For instance, if a purchaser sent 10 bitcoins and the total bitcoins sent that day were 100 bitcoins than the purchaser would have 10% (200) of the 2,000 APIcoins sold that day.
2. Starting on June 18th 2014, anyone sending bitcoins to the "API Address" before July 18th, 2014 is recognized by the protocol as owning X (multiple to be determined by the average price during the 7 dutch auction days) that number of APICoins. For instance, if the user sends 100 bitcoins to the "API Address" before July 18th, their bitcoin address owns 100 times X APIcoins after July 18th. 
3. In order to encourage adoption momentum, buyers will get an additional 10% bonus APICoinss if they make their purchase a week before the deadline, 20% extra if they purchase two weeks weeks before, and so on, including partial weeks, prorating the total purchase accordingly. Thus, if I send 100 bitcoins to the "API Address" 1.5 weeks before the 18th of July 2014, the protocol recognizes my bitcoin address as owning 11,500 APICoinss (10000 + 15% bonus).
4. Attempts to send funds to the API "Address" on or after midnight (central time) July 18th 2014 (as determined by bitcoin block chain records) will not be considered APICoins purchases and shall be sent back to the originating Bitcoin wallets in the form of Bitcoin minus transaction fees.
5. The total number of APIcoins generated during the crowdsale shall be limited to 200,000 any APIcoins generated after this point shall be invalid and the bitcoin sent for their generate returned to the sender.

In the event that a purchase has multiple inputs, the input address contributing the most funds is recognized as owning the APICoins.

Note that anyone who purchases APICoins also receive the ability to test new features before they are available for use in the API Network Protocol.

## Developer APICoins (Dev Tokens)

For every 4 APICoin sold, an additional “Developer APICoins” will also be created, which will be awarded to the API Address slowly over the following years. These delayed API Tokens will ensure that the community can incentivize developers to increase the value of API Token by completing the features desired by users. The reward will be structured so that the distributed bounty system receives the tokens on a logarithmic scale: 50% of all the Dev API Tokens by one year after the initial sale, 75% by a year later, 87.5% by the year after, and so on.

SAFE coins generated by the use of API's published on the API Network will be sent to the API Network developer pool purchase APICoins on the Decentralized Exchange and hold them for release to contributors to the API Network open source code.

## Transferring APICoins

The transfer of APICoins will is done through the Master Protocol client implimetations.

Note that the amount to transfer is accounted for in Lacys (hundred million Lacy's add up to make 1 APICoin) before it is stored, which allows for APICoins to be sent with the same precision as bitcoins (eight decimal places).

