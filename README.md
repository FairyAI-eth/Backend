# Backend of Obo the Fairy

Obo is a Fairy that will onboard you on any chain and any DeFi project in a single wave of her magic wand.

![Obo image](./obo.jpg)

## User journey

1. User choose their action (MVP: chain to onboard on)
2. Connect their wallet
3. We scan their assets (sponsor API?)
4. Find which token to swap, which bridge to use
5. give the user an overview of the transaction and a button "Launch"

Users would pay by a single token transfer covering all costs, the fairy will swap those tokens accordingly and keep a small fee for gas (fairy dust).

## Tech Stack

The fairy will interact with the chain using Coinbase Agent Kit. IntentKit from Crestal Network could also work? 
Look into onchain Kit from coinbase and if it might help.

Prize: One of (Innovative use of AgentKit, Best agent using other CDP tools (onramp), Viral consumer app, Agentic Payments), Pool prize

We can deploy make Base the "base chain". 
Prize: up to 2k

To get an overview of users' assets, either an API or TheGraph (if a subgraph exists).
Prize: up to 2.5k

Could use AWS Bedrock for RAG and queries:
Prize: 1k


### Improvements

- Sign in with Privy (email login) and pay with Coinbase onramp. If we implement that we may keep credit/debit card data on-chain using Lit protocol (as a last last improvement).


