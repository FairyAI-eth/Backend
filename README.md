# Backend of Eve the Fairy

Eve is a Fairy that will onboard you on any chain and any DeFi project in a single wave of her magic wand.

## User journey

1. User choose their action (MVP: chain to onboard on)
2. Connect their wallet
3. We scan their assets (sponsor API?)
4. Find which token to swap, which bridge to use
5. give the user an overview of the transaction and a button "Launch"

Users would pay by a single token transfer covering all costs, the fairy will swap those tokens accordingly and keep a small fee for gas (fairy dust).

## Tech Stack

The fairy will interact with the chain using Coinbase Agent Kit.
