---
layout: post
type: socratic
title: "Socratic Seminar #26"
meetup: https://www.meetup.com/bitdevsldn/events/294227571/
---

## Announcements

Please join us for our next Socratic Seminar. This Socratic Seminar is sponsored by [Brink](https://brink.dev).
Please speak to the hosts if you're interested in supporting London BitDevs.

## General Links

* [Bitcoin Optech](https://bitcoinops.org)
* [Bitcoin Core PR Review Club](https://bitcoincore.reviews)
* [bitcoin-dev Mailing List](https://lists.linuxfoundation.org/pipermail/bitcoin-dev)
* [lightning-dev Mailing List](https://lists.linuxfoundation.org/pipermail/lightning-dev)

## Mailing Lists, Meetings and Bitcoin Optech
### Mailing Lists
#### [bitcoin-dev](https://lists.linuxfoundation.org/pipermail/bitcoin-dev)
- [Scaling and anonymizing Bitcoin at layer 1 with client-side validation](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-June/021732.html)
- [Standardisation of an unstructured taproot annex](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-June/021731.html)
- [Conceptual package relay using taproot annex](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-June/thread.html)
- [BIP for Silent Payments](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-June/021750.html)
- [CivKit Node v0.0.1 release - "Sic itur ad astra"](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-June/021779.html)

#### [lightning-dev](https://lists.linuxfoundation.org/pipermail/lightning-dev)
- [Proposal to extend BOLT11 invoices to request two payments](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-June/003977.html)


### Meetings
- [Bitcoin PR Review Club](https://bitcoincore.reviews)
  - [#27145 When a block is disconnected, update transactions that are no longer conflicted](https://bitcoincore.reviews/27145)
  - [#27711 Remove shutdown from kernel library](https://bitcoincore.reviews/27711)
  - [#27625 Stop relaying non-mempool txs](https://bitcoincore.reviews/27625)
  - [#27748 util: generalize accounting of system-allocated memory in pool resource](https://bitcoincore.reviews/27748)

### Optech
- [Newsletter #253](https://bitcoinops.org/en/newsletters/2023/05/31/), [audio recap](https://bitcoinops.org/en/podcast/2023/06/01/)
- [Newsletter #254](https://bitcoinops.org/en/newsletters/2023/06/07/), [audio recap](https://bitcoinops.org/en/podcast/2023/06/08/)
- [Newsletter #255](https://bitcoinops.org/en/newsletters/2023/06/14/), [audio recap](https://bitcoinops.org/en/podcast/2023/06/15/)
- [Newsletter #256](https://bitcoinops.org/en/newsletters/2023/06/21/), [audio recap](https://bitcoinops.org/en/podcast/2023/06/22/)

## Network Data
-

## CVEs and Research
### Research
- [Securing a $100M Lightning node](https://acinq.co/blog/securing-a-100M-lightning-node)

## Pull Requests and repo updates
### [Bitcoin Core](https://github.com/bitcoin/bitcoin)
- [mempool / rpc: add getprioritisedtransactions, delete a mapDeltas entry when delta==0](https://github.com/bitcoin/bitcoin/pull/27501)
- [Fee estimation: avoid serving stale fee estimate](https://github.com/bitcoin/bitcoin/pull/27622)
- [BIP324: ElligatorSwift integrations](https://github.com/bitcoin/bitcoin/pull/27479)
- [p2p: Stop relaying non-mempool txs](https://github.com/bitcoin/bitcoin/pull/27625)
- [p2p: give seednodes time before falling back to fixed seeds](https://github.com/bitcoin/bitcoin/pull/27577)


### [LND](https://github.com/lightningnetwork/lnd)
- [lnd v0.16.3-beta](https://github.com/lightningnetwork/lnd/releases/tag/v0.16.3-beta)
- [sweep+lnrpc:enforce provided fee rate is no less than relay fee](sweep+lnrpc: enforce provided fee rate is no less than relay fee)
- [contractcourt: force the sweeper to always resolve outgoing HTLCs](https://github.com/lightningnetwork/lnd/pull/7726)

### [LDK](https://github.com/lightningdevkit/rust-lightning)
- [disconnect peers on timer ticks to unblock channel state machine](https://github.com/lightningdevkit/rust-lightning/pull/2293)
- [BOLT12 offers message handling support](https://github.com/lightningdevkit/rust-lightning/pull/2294)
- [Support MPP Keysend](https://github.com/lightningdevkit/rust-lightning/pull/2156)

### [Eclair](https://github.com/ACINQ/eclair)
- [Eclair v0.9.0](https://github.com/ACINQ/eclair/releases/tag/v0.9.0)
- [Relax reserve requirements on HTLC receiver](https://github.com/ACINQ/eclair/pull/2666)
- [Add upper bound on fees paid during force-close](https://github.com/ACINQ/eclair/pull/2668)
- [Add `closedchannels RPC`](https://github.com/ACINQ/eclair/pull/2642)
- [Increase default max-cltv value](https://github.com/ACINQ/eclair/pull/2677)

### [Core-Lightning](https://github.com/ElementsProject/lightning)
- [v23.05.1: Austin Texas Agreement (ATXA) 2](https://github.com/ElementsProject/lightning/releases/tag/v23.05.1)
- [Configuration rework](https://github.com/ElementsProject/lightning/pull/6243)

### [Bitcoin-inquisition](https://github.com/bitcoin-inquisition/bitcoin)
-

### [BIP]
- [BIP 329: Add spendable state to outputs](https://github.com/bitcoin/bips/pull/1452)

