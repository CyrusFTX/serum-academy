---
date: 2020-08-30T00:0:00+00:00
title: Project Ideas for Serum
weight: 2
---

## Project Ideas

### AMM Bot

Building an open source system that people can use to achieve AMM-like behavior on Serum’s orderbooks.

Details can be found on Ecoserum website: https://www.ecoserum.dev/

### Dumplings

A yield farming token that is integrated into an AMM system on Serum.

Here is an idea of what it could look like:

- Build a "pool" which starts at 100 SRM + 100 SOL per pool token. It's just an ETF — you can't actually trade against the pool.

- The pool automatically does the on-chain AMM-style market making on the Serum SRM/SOL market. Basically this means; a liquidity providing strategy such that, if SRM/SOL goes from price A → B → A, the pool’s valuation will at worst be unchanged. The pool will be fully on-chain and its behavior will be well defined from creation.

- You can 'create' into the pool by delivering the basket. So at the beginning if you send in 200 SRM + 200 SOL you get 2 SPT (Serum Pool Tokens). If after an hour of trading the pool was 150 SRM + 80 SOL then to create 2 SPT you'd deposit 300 SRM + 160 SOL.

- You can redeem your SPTs for the fractional share of the pool.

- The pool gets the proceeds of its trading, including maker rebates

- Each day, 10,000 Dumplings are added to the pool for the first 100 days; then no more Dumplings are created. When a Dumpling contract is first created, 100,000 Dumplings (DUM) are airdropped on all SRM holders to seed liquidity for joining the pool.

This means that:

- If you redeem your SPTs after 5 days and you were half the pool, you'd get back your SRM/SOL, and also 25,000 Dumplings. You can trade those on the DUM/USDC market or whatever.

- If after 5 days you want to _join_ the SRM/SOL MM pool for, say, 100 SRM + 100 SOL, you'd have to send in: 100 SRM, 100 SOL, and some DUM (maybe 15,000, depending on how large the pool had been/how many DUM are in 1 SPT).

This means that entering the MM pool is gated by buying/owning Dumplings, and you get Dumplings each day for providing liquidity.

### Borrow/Lending

Serum needs a borrow/lending protocol. This could be either:

- A home-brewed version

- One of the major Ethereum based protocols (Compound, Aave Aave, etc.) building a mirror on Solana

Furthermore, this can then be composed on top of Serum orderbooks to create margin trading.

### Cross-Chain Bridges

It would be awesome to have fully on-chain bridges between Solana and as many other chains as possible. See prospective specs for one here, but there are many other versions!

### Cross-Chain Lending

Assets can be pre-funded across the bridge and allow users to avoid waiting for cross-chain synchronization for a fee. For example, a user could deposit X eth into the bridge as collateral, and be able to withdraw any pre-funded assets up to some limit.

### Serum Oracle

An on-chain oracle that takes prices from Serum markets, does sophisticated risk and sanity checks on them, and creates a clean price feed that other projects working on Serum can use. Furthermore, once there are on-chain cross-chain bridges, those can be combined with this to create a fully on-chain cross-chain pricing oracle.

### Serum RFQ

Generate a tradable RFQ from the Serum order book. The generated quote can be valid for a limited time and backed by an insurance pool. It would have a size attached, and potentially be larger and wider than would be typical for orderbook trading.

### Decentralized Wrappers

An on-chain method of wrapping an ERC20 token into an SPL token and vice versa.

### Synthetic Assets

Building out support for tokenized synthetic assets on Serum.

### Volatility Products

Building out markets or tokenized products representing volatility or other nonlinear functions of markets.

### Zero Knowledge Liquidation Engine

PoC for ZK liquiditations, where it’s zk to the network, but not zk to the defi platform operators. The engine should be able to use the on chain order book price or funding rate as a witness, and generate a proof that states the contract is now ‘in the money’ or ‘out of the money’ and take an action from there.

### Native Metamask Integration

See this introduction to Web3 Plugins for more details

### Mobile App

A mobile app for Serum that also lets you self-custody on mobile.

### Badges

Badges to represent participation in various aspects of Serum; e.g. liquidity providing, node operating.

### GUI & Other Ideas

Below is a list of GUI & other features that could be developed:

- Button on [Sollet.io](https://sollet.io) to mint your own SPL token
- Graphs on the DEX GUI
- Button to create a Serum market
- Market orders on GUI
- Ledger support for [Sollet.io](https://sollet.io)
- Volume and other metric trackers for Serum
- A tool to validate GUIs against the source code

See Project Serum [GitHub account](https://github.com/project-serum/) for the source of [Sollet.io](https://sollet.io) and the [DEX GUI](/en/dex-list)
