# Nolus Cross-Ledger Messaging

Messaging proposal between different Ledgers (Blockchain and non-Blockchain) to and from Nolus AppChain and any other IBC/Cosmos SDK Appchain.

[Idea Builder](https://ideabuilder.ibcprotocol.dev/) Template on IPFS: https://ipfs.filebase.io/ipfs/Qmbi2MuecB1WcYd8EjWBU4CCwV1yR6ArxzoxdqsQyNnaMp

## Architecture



## Description 
For this new architecture, which allows Nolus to connect to different networks (both Blockchain and non-Blockchain), the use of **Interledger Protocol** (https://interledger.org/) is proposed. Here are the benefits for Nolus and all its components:

1. **Extended interoperability**: Interledger Protocol (ILP) works under a TCP/IP-like scheme, using messages that can include all kinds of data, allowing Nolus to connect to EVM, SVM, and Move networks, among others, through smart contracts, as well as to Blockchain networks that do not have smart contracts (such as XRPL and Stellar), as well as non-Blockchain networks, such as PayPal, Stripe, and numerous centralized services.
2. **Independence**: ILP's flexibility also occurs in the connectors (which allow communication) and which can be completely managed by Nolus, making it easy to adapt to any environment without depending on other networks.

All the details: https://drive.google.com/file/d/1gPV6wyPxPWX2dkUto7m-balZlkfIuB5t/view?usp=sharing
