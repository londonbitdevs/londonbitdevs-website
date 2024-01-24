---
layout: post
type: socratic
title: "Socratic Seminar #31"
meetup: https://www.meetup.com/bitdevsldn/events/298417934
---

## Announcements

Please join us for our next Socratic Seminar. This Socratic Seminar is sponsored by [Ben Delo](https://twitter.com/bendelo).
Please speak to the hosts if you're interested in supporting London BitDevs.

## General Links

* [Bitcoin Optech](https://bitcoinops.org)
* [Bitcoin Core PR Review Club](https://bitcoincore.reviews)
* [bitcoin-dev Mailing List](https://lists.linuxfoundation.org/pipermail/bitcoin-dev)
* [lightning-dev Mailing List](https://lists.linuxfoundation.org/pipermail/lightning-dev)

## Mailing Lists, Meetings and Bitcoin Optech
### Mailing Lists
#### [bitcoin-dev](https://lists.linuxfoundation.org/pipermail/bitcoin-dev)
- [Bitcoin Core 26.0 released](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-December/022187.html)
- [Altruistic Rebroadcasting - A Partial Replacement Cycling Mitigation](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-December/022188.html)
- [Lamport scheme (not signature) to economize on L1](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-December/022201.html)
- [Scaling Lightning Safely With Feerate-Dependent Timelocks](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-December/022191.html)
- [V3 Transactions are still vulnerable to significant tx pinning griefing attacks](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-December/022211.html)
- [Compressed Bitcoin Transactions](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2024-January/022269.html)
- [Introducing a version field to BIP39 mnemonic phrases](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2024-January/022275.html)
- [BitBlend Proposal for 2106](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2024-January/022285.html)
- [One-Shot Replace-By-Fee-Rate](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2024-January/022298.html)


#### [lightning-dev](https://lists.linuxfoundation.org/pipermail/lightning-dev)
-

### Meetings
- [Bitcoin PR Review Club](https://bitcoincore.reviews)
  - [#28690 Introduce internal kernel library](https://bitcoincore.reviews/28690)
  - [#28956 Nuke adjusted time (attempt 2)](https://bitcoincore.reviews/28956)

### Optech
- [Newsletter #279](https://bitcoinops.org/en/newsletters/2023/11/29/), [audio recap](https://bitcoinops.org/en/podcast/2023/11/30/)
- [Newsletter #280](https://bitcoinops.org/en/newsletters/2023/12/06/), [audio recap](https://bitcoinops.org/en/podcast/2023/12/07/)
- [Newsletter #281](https://bitcoinops.org/en/newsletters/2023/12/13/), [audio recap](https://bitcoinops.org/en/podcast/2023/12/14/)
- [Newsletter #282](https://bitcoinops.org/en/newsletters/2023/12/20/), [audio recap](https://bitcoinops.org/en/podcast/2023/12/21/)
- [Newsletter #283](https://bitcoinops.org/en/newsletters/2023/12/27/), [audio recap](https://bitcoinops.org/en/podcast/2023/12/28/)
- [Newsletter #284](https://bitcoinops.org/en/newsletters/2024/01/03/), [audio recap](https://bitcoinops.org/en/podcast/2024/01/04/)
- [Newsletter #285](https://bitcoinops.org/en/newsletters/2024/01/10/), [audio recap](https://bitcoinops.org/en/podcast/2024/01/11/)
- [Newsletter #286](https://bitcoinops.org/en/newsletters/2024/01/17/), [audio recap](https://bitcoinops.org/en/podcast/2024/01/18/)
- [Newsletter #287](https://bitcoinops.org/en/newsletters/2024/01/24/), [audio recap](https://bitcoinops.org/en/podcast/2024/01/25/)

## Network Data
-

## CVEs and Research
### Research
- [Ledger Connect Kit](https://www.ledger.com/blog/security-incident-report)

### InfoSec
-

## Pull Requests and repo updates
### [Bitcoin Core](https://github.com/bitcoin/bitcoin)
<!--- Link to query merged PRs since YYYY-MM-DD sorted by descending activity: https://github.com/bitcoin/bitcoin/pulls?page=1&q=is%3Apr+is%3Aclosed+merged%3A%3EYYYY-MM-DD+sort%3Acomments-desc -->
- [net, cli: use v2transport for manual/addrfetch connections, add to -netinfo](https://github.com/bitcoin/bitcoin/pull/29058)
- [rpc: Make v2transport default for addnode RPC when enabled](https://github.com/bitcoin/bitcoin/pull/29239)
- [Fee Estimator updates from Validation Interface/CScheduler thread](https://github.com/bitcoin/bitcoin/pull/28368)
- [wallet: Pass through transaction locktime and preset input sequences and scripts to CreateTransaction](https://github.com/bitcoin/bitcoin/pull/25273)
- [wallet: skip BnB when SFFO is enabled](https://github.com/bitcoin/bitcoin/pull/28994)
- [doc: Add multiprocess design doc](https://github.com/bitcoin/bitcoin/pull/28978)
- [rpc: encryptwallet help, mention HD seed rotation and backup requirement](https://github.com/bitcoin/bitcoin/pull/28980)
- [log mempool loading progress](https://github.com/bitcoin/bitcoin/pull/29227)

### [LND](https://github.com/lightningnetwork/lnd)
-

### [LDK](https://github.com/lightningdevkit/rust-lightning)
-

### [Eclair](https://github.com/ACINQ/eclair)
-

### [Bitcoin-inquisition](https://github.com/bitcoin-inquisition/bitcoin)
- [LNHANCE inquisition (CSFS, INTERNALKEY)](https://github.com/bitcoin-inquisition/bitcoin/pull/45)
- [getdeploymentinfo: Report BINANA ids](https://github.com/bitcoin-inquisition/bitcoin/pull/47)

### [BIPs](https://github.com/bitcoin/bips)
- [BIP process friction](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2024-January/022289.html)
- [Ephemeral anchors](https://github.com/bitcoin/bips/pull/1524)
- [BIP for reenabling OP\_CAT](https://github.com/bitcoin/bips/pull/1525)
- [Opt-In Policy For More Robust Fee-bumping](https://github.com/bitcoin/bips/pull/1541)
- [64bit arithmetic op codes](https://github.com/bitcoin/bips/pull/1538)
- [Add bip-internalkey](https://github.com/bitcoin/bips/pull/1534)
- [Add bip-csfs OP\_CHECKSIGFROMSTACK(VERIFY)](https://github.com/bitcoin/bips/pull/1535)
- [BIPs for MuSig2 derivation, descriptors, and PSBT fields](https://github.com/bitcoin/bips/pull/1540)

### [BOLT]
-

## New Releases
-

## Events and Podcasts
-

## Mining
-

## Privacy
-

## Miscellaneous
- [RFC: Deprecate libconsensus](https://github.com/bitcoin/bitcoin/pull/29189)
- [Ord Release 0.15.0](https://github.com/ordinals/ord/releases/tag/0.15.0)
- [Vindication](https://github.com/ordinals/ord/pull/2950)
- [Delegation](https://github.com/ordinals/ord/pull/2912)
