---
layout: post
type: socratic
title: "Socratic Seminar #37"
meetup: https://www.meetup.com/bitdevsldn/events/302685292 
---

## Announcements

Please join us for our next Socratic Seminar. This Socratic Seminar is sponsored by [Ben Delo](https://twitter.com/bendelo).
Please speak to the hosts if you're interested in supporting London BitDevs.

## General Links

* [Bitcoin Optech](https://bitcoinops.org)
* [Bitcoin Core PR Review Club](https://bitcoincore.reviews)
* [bitcoin-dev Mailing List](https://lists.linuxfoundation.org/pipermail/bitcoin-dev)
* [lightning-dev Mailing List](https://lists.linuxfoundation.org/pipermail/lightning-dev)

## Delving Bitcoin, Mailing Lists, Meetings and Bitcoin Optech
### [Delving Bitcoin](https://delvingbitcoin.org/)
- [Zawy's Alternating Timestamp Attack](https://delvingbitcoin.org/t/zawy-s-alternating-timestamp-attack/1062)
- [Non interactive anti-exfil (airgap compatible)](https://delvingbitcoin.org/t/non-interactive-anti-exfil-airgap-compatible/1081)
- [Optimistic ZK verification using MATT](https://delvingbitcoin.org/t/optimistic-zk-verification-using-matt/1050)
- [Stats on compact block reconstructions](https://delvingbitcoin.org/t/stats-on-compact-block-reconstructions/1052)
- [Bolt 12 Trusted Contacts](https://delvingbitcoin.org/t/bolt-12-trusted-contacts/1046)
- [Onion Messaging DoS Threat Mitigations](https://delvingbitcoin.org/t/onion-messaging-dos-threat-mitigations/1058)

### Mailing Lists
#### [bitcoindev](https://groups.google.com/g/bitcoindev)
- [Bitcoin Core's migration to the CMake buildsystem](https://groups.google.com/g/bitcoindev/c/hgKkfQWzrTo)
- [Public disclosure of 2 vulnerabilities affecting Bitcoin Core < v22.0](https://groups.google.com/g/bitcoindev/c/01goVlOCjBA)

### Meetings
- [Bitcoin PR Review Club](https://bitcoincore.reviews)
  - [#30352 Add PayToAnchor(P2A), OP 1 <0x4e73> as standard output script for spending](https://bitcoincore.reviews/30352)

### Optech
- [Newsletter #314](https://bitcoinops.org/en/newsletters/2024/08/02/), [audio recap](https://bitcoinops.org/en/podcast/2024/08/06/)
- [Newsletter #315](https://bitcoinops.org/en/newsletters/2024/08/09/), [audio recap](https://bitcoinops.org/en/podcast/2024/08/13/)
- [Newsletter #316](https://bitcoinops.org/en/newsletters/2024/08/16/), [audio recap](https://bitcoinops.org/en/podcast/2024/08/20/)
- [Newsletter #317](https://bitcoinops.org/en/newsletters/2024/08/23/), [audio recap](https://bitcoinops.org/en/podcast/2024/08/27/)

## CVEs and Research
### Research
- [New multiplication algorithm for Circle STARK](https://hackmd.io/@l2iterative/Byg8h1MsC)
- [Engineering a backdoored bitcoin wallet](https://www.usenix.org/system/files/woot24-scott.pdf)

### InfoSec
- [Dark Skippy](https://darkskippy.com/) (and some [related discussion](https://x.com/TheBlueMatt/status/1820533237661544863))

## Pull Requests and repo updates
### [Bitcoin Core](https://github.com/bitcoin/bitcoin)
<!--- Link to query merged PRs since YYYY-MM-DD sorted by descending activity: https://github.com/bitcoin/bitcoin/pulls?page=1&q=is%3Apr+is%3Aclosed+merged%3A%3EYYYY-MM-DD+sort%3Acomments-desc -->
- [Don't empty dbcache on prune flushes: >30% faster IBD](https://github.com/bitcoin/bitcoin/pull/28280)
- [cluster mempool: cluster linearization algorithm](https://github.com/bitcoin/bitcoin/pull/30126)
- [Testnet4 including PoW difficulty adjustment fix](https://github.com/bitcoin/bitcoin/pull/29775)
- [policy: Add PayToAnchor(P2A), `OP_1 <0x4e73>` as a standard output script for spending](https://github.com/bitcoin/bitcoin/pull/30352)
- [blockstorage: XOR blocksdir \*.dat files](https://github.com/bitcoin/bitcoin/pull/28052)
- [policy: enable full-rbf by default](https://github.com/bitcoin/bitcoin/pull/30493)
- [assumeutxo: Drop block height from metadata](https://github.com/bitcoin/bitcoin/pull/30598)
- [validation: assumeutxo params mainnet](https://github.com/bitcoin/bitcoin/pull/28553)
- [Have miner account for timewarp mitigation, activate on regtest, lower nPowTargetTimespan to 144 and add test](https://github.com/bitcoin/bitcoin/pull/30681)
- [Move maximum timewarp attack threshold back to 600s from 7200s](https://github.com/bitcoin/bitcoin/pull/30647)

## New Releases
- [ARK v0.2](https://arkdev.info/blog/ark-release-v0.2/)
- [Floresta Update: Simplifying Bitcoin Node Integration for Wallets](https://medium.com/vinteum-org/floresta-update-simplifying-bitcoin-node-integration-for-wallets-6886ea7c975c)
- [BDK 1.0.0-beta.1](https://github.com/bitcoindevkit/bdk/releases/tag/v1.0.0-beta.1)

## Miscellaneous
- ["`OP_CAT alone` and the Great Script Restoration enable exactly the same constructions on bitcoin."](https://x.com/salvatoshi/status/1822199971547947234)
- ["Prevent the CATastrophe"](https://gist.github.com/RobinLinus/fdee133af13948b0e617f9ef4f8b8752)
