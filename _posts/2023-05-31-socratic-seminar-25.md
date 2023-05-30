---
layout: post
type: socratic
title: "Socratic Seminar #25"
meetup: https://www.meetup.com/bitdevsldn/events/293634569/
---

## Announcements

Please join us for our next Socratic Seminar. This Socratic Seminar is sponsored by [Kingsway Capital](https://www.kingswaycap.com/).
Please speak to the hosts if you're interested in supporting London BitDevs.

## General Links

* [Bitcoin Optech](https://bitcoinops.org)
* [Bitcoin Core PR Review Club](https://bitcoincore.reviews)
* [bitcoin-dev Mailing List](https://lists.linuxfoundation.org/pipermail/bitcoin-dev)
* [lightning-dev Mailing List](https://lists.linuxfoundation.org/pipermail/lightning-dev)

## Mailing Lists, Meetings and Bitcoin Optech
### Mailing Lists
#### [bitcoin-dev](https://lists.linuxfoundation.org/pipermail/bitcoin-dev)
- [Ark: An Alternative Privacy-preserving Second Layer Solution](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-May/021694.html)
- [On adaptor security (in protocols)](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-May/021597.html)
- [proposal: new opcode OP_ZKP to enable ZKP-based spending authorization](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-May/021598.html)
- [Merkleize All The Things](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-May/021599.html)
- [Bitcoin Core maintainers and communication on merge decisions](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-May/021618.html)
- [Should we as developers reject non-standard Taproot transactions from full nodes?](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-May/021620.html)
- [tx max fee](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-May/021621.html)
- [Witness script validation to reject arbitrary data](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-May/021630.html)
- [Responsible disclosures and Bitcoin development](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-May/021643.html)
- [libsecp256k1 0.3.2 released](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-May/021683.html)
- [ZeroSync: Introducing Validity Proofs to Bitcoin](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-May/021679.html)
- [Coinjoin with less steps using ALL|ANYONECANPAY](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-May/021696.html)

#### [lightning-dev](https://lists.linuxfoundation.org/pipermail/lightning-dev)
- [HTLC Endorsment for Jamming Mitigation](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-April/003918.html)
- [Call for Review - LSPSpec LSPS1 LSPS2](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-May/003926.html)
- [Liquidity griefing for 0-conf dual-funded txs](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-May/003920.html)

### Meetings
- [Bitcoin PR Review Club](https://bitcoincore.reviews)
  - [#27501 Add getprioritisationmap, delete a mapDeltas entry when delta==0](https://bitcoincore.reviews/27501)
  - [#26485 Accept options as named-only parameters](https://bitcoincore.reviews/26485)
  - [#27600 Allow inbound whitebind connections to more aggressively evict peers when slots are full](https://bitcoincore.reviews/27600)
  - [Testing Bitcoin Core 25.0 Release Candidates](https://bitcoincore.reviews/v25-rc-testing)

### Optech
- [Newsletter #249](https://bitcoinops.org/en/newsletters/2023/05/03/), [audio recap](https://bitcoinops.org/en/podcast/2023/05/04/)
- [Newsletter #250](https://bitcoinops.org/en/newsletters/2023/05/10/), [audio recap](https://bitcoinops.org/en/podcast/2023/05/11/)
- [Newsletter #251](https://bitcoinops.org/en/newsletters/2023/05/17/), [audio recap](https://bitcoinops.org/en/podcast/2023/05/18/)
- [Newsletter #252](https://bitcoinops.org/en/newsletters/2023/05/24/), [audio recap](https://bitcoinops.org/en/podcast/2023/05/25/)

## CVEs and Research

### InfoSec
- [Ledger Recover Feature](https://www.ledger.com/recover)
- [Threat Model](https://donjon.ledger.com/threat-model/)
- [Threat Model - Genuineness](https://donjon.ledger.com/threat-model/device-genuineness/)
- [Threat Model - Secure Display and Inputs](https://donjon.ledger.com/threat-model/device-secure-display-and-inputs/)
- [Threat Model - Physical Resistance](https://donjon.ledger.com/threat-model/device-physical-resistance/)
- [Threat Model - PIN Security Mechanism](https://donjon.ledger.com/threat-model/os-pin-security-mechanism/)
- [Threat Model - Random Number Generation](https://donjon.ledger.com/threat-model/os-random-number-generation/)
- [Threat Model - Confidentiality of Seed and Private Keys](https://donjon.ledger.com/threat-model/os-seed-confidentiality/)
- [Threat Model - Confidentiality and Integrity](https://donjon.ledger.com/threat-model/os-confidentiality-and-integrity/)
- [Threat Model - Transport Security](https://donjon.ledger.com/threat-model/os-transport-security/)
- [Threat Model - App Isolation](https://donjon.ledger.com/threat-model/app-isolation/)
- [Threat Model - User Content](https://donjon.ledger.com/threat-model/app-user-consent/)


## Pull Requests and repo updates
### [Bitcoin Core](https://github.com/bitcoin/bitcoin)
- [New Mempool Design](https://github.com/bitcoin/bitcoin/issues/27677)
- [Improve performance of p2p inv to send queues](https://github.com/bitcoin/bitcoin/pull/27610)
- [Parallel compact block downloads, take 3](https://github.com/bitcoin/bitcoin/pull/27626)
- [Implement Mini version of BlockAssembler to calculate mining scores](https://github.com/bitcoin/bitcoin/pull/27021)
- [add ryanofsky to trusted-keys](https://github.com/bitcoin/bitcoin/pull/27604)
- [rpc: add descriptorprocesspsbt rpc](https://github.com/bitcoin/bitcoin/pull/25796)
- [wallet: improve IBD sync time by skipping block scanning prior birth time](https://github.com/bitcoin/bitcoin/pull/27469)
- [wallet: when a block is disconnected, update transactions that are no longer conflicted](https://github.com/bitcoin/bitcoin/pull/27145)


### [LND](https://github.com/lightningnetwork/lnd)
- [Add config options for custom features bits](https://github.com/lightningnetwork/lnd/pull/7568)
- [multi: accept memo note when opening channel](https://github.com/lightningnetwork/lnd/pull/7668)

### [LDK](https://github.com/lightningdevkit/rust-lightning)
- [Support broadcasting multiple transactions at once](https://github.com/lightningdevkit/rust-lightning/pull/2272)
- [Implement pending claim rebroadcast on force-closed channels](https://github.com/lightningdevkit/rust-lightning/pull/2208)
- [Add function for updating network graph with announcement with no UTXO resolver](https://github.com/lightningdevkit/rust-lightning/pull/2222)
- [Limit route hints to three channels](https://github.com/lightningdevkit/rust-lightning/pull/2044)
- [Create and Sign PSBTs for spendable outputs](https://github.com/lightningdevkit/rust-lightning/pull/2286)
- [Dual funding and interactive tx construction wire messages](https://github.com/lightningdevkit/rust-lightning/pull/1794)
- [Support for custom feature bits](https://github.com/lightningdevkit/rust-lightning/pull/2204)
- [Post-anchor: do not aggregate claim of revoked output](https://github.com/lightningdevkit/rust-lightning/pull/1841)

## New Releases
- [Bitcoin Core 23.2](https://bitcoincore.org/bin/bitcoin-core-23.2)
- [Bitcoin Core 24.1](https://bitcoincore.org/bin/bitcoin-core-24.1)
- [Bitcoin Core 25.0 Release Candidates](https://bitcoincore.org/bin/bitcoin-core-25.0)

## Miscellaneous
- [mempool.space announced an accelerator service](https://twitter.com/mempool/status/1659619347910803466)
- [Introducing Phantom Node Payments](https://lightningdevkit.org/blog/introducing-phantom-node-payments/)
