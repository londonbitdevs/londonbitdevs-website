---
layout: post
type: socratic
title: "Socratic Seminar #23"
meetup: https://www.meetup.com/bitdevsldn/events/292356513/
---

## Announcements

Please join us for our next Socratic Seminar. This Socratic Seminar is sponsored by [The Label](https://thelab31.xyz/).
Please speak to the hosts if you're interested in supporting London BitDevs.

## General Links

* [Bitcoin Optech](https://bitcoinops.org)
* [Bitcoin Core PR Review Club](https://bitcoincore.reviews)
* [bitcoin-dev Mailing List](https://lists.linuxfoundation.org/pipermail/bitcoin-dev)
* [lightning-dev Mailing List](https://lists.linuxfoundation.org/pipermail/lightning-dev)

## Mailing Lists, Meetings and Bitcoin Optech
### Mailing Lists
#### [bitcoin-dev](https://lists.linuxfoundation.org/pipermail/bitcoin-dev)
- [Refreshed BIP324](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-February/021491.html)
- [BIP proposal: Fee-redistribution contracts](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-February/021505.html)
- [Codex32](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-February/021469.html)
- [Using service bit 24 for utreexo signaling in testnet and signet](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-March/021515.html)
- [BIP for OP_VAULT](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-March/021510.html)
- [Minimum fees](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-March/021512.html)

#### [lightning-dev](https://lists.linuxfoundation.org/pipermail/lightning-dev)
- [Highly Available Lightning Channels](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-February/003842.html)
- [On watchtowers and accumulators](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-March/003892.html)

### Meetings
- [Bitcoin PR Review Club](https://bitcoincore.reviews)
    - #25038 nVersion=3 and Package RBF [part 1](https://bitcoincore.reviews/25038) and [part 2](https://bitcoincore.reviews/25038-2)
    - [#25325 Add pool based memory resource](https://bitcoincore.reviews/25325)
    - [#27006 Reduce cs_main scope, guard block index 'nFile' under a local mutex](https://bitcoincore.reviews/27006)
    - [#27050 Don't download witnesses for assumed-valid blocks when running in prune mode](https://bitcoincore.reviews/27050)
    - [#26403 Ephemeral Anchors](https://bitcoincore.reviews/26403)

### Optech
- [Newsletter #240](https://bitcoinops.org/en/newsletters/2023/03/01/), [audio recap](https://bitcoinops.org/en/podcast/2023/03/02/)
- [Newsletter #241](https://bitcoinops.org/en/newsletters/2023/03/08/), [audio recap](https://bitcoinops.org/en/podcast/2023/03/09/)
- [Newsletter #242](https://bitcoinops.org/en/newsletters/2023/03/15/), [audio recap](https://bitcoinops.org/en/podcast/2023/03/16/)
- [Newsletter #243](https://bitcoinops.org/en/newsletters/2023/03/22/), [audio recap](https://bitcoinops.org/en/podcast/2023/03/23/)

## Network Data
- [Default mempools full, minimum feerate consistently above 1sat/vB](https://twitter.com/murchandamus/status/1640324981140733953?s=20)

## Pull Requests and repo updates
### [Bitcoin Core](https://github.com/bitcoin/bitcoin)
- [#27255: MiniTapscript: port Miniscript to Tapscript](https://github.com/bitcoin/bitcoin/pull/27255)
- [#27261: Ignore datacarrier limits for dataless OP_RETURN outputs](https://github.com/bitcoin/bitcoin/pull/27261)
- [#27213: p2p: Diversify automatic outbound connections with respect to networks](https://github.com/bitcoin/bitcoin/pull/27213)
- [#27101: Support JSON-RPC 2.0 when requested by client](https://github.com/bitcoin/bitcoin/pull/27101)
- [#27278: Log new headers](https://github.com/bitcoin/bitcoin/pull/27278)
- [#27068: wallet: SecureString to allow null characters](https://github.com/bitcoin/bitcoin/pull/27068)
- [#25740: assumeutxo: background validation completion](https://github.com/bitcoin/bitcoin/pull/25740)
- [#26177: refactor / kernel: Move non-gArgs chainparams functionality to kernel](https://github.com/bitcoin/bitcoin/pull/26177)
- [#26531: mempool: Add mempool tracepoints](https://github.com/bitcoin/bitcoin/pull/26531)

### [LND](https://github.com/lightningnetwork/lnd)
- [#765 lnwallet: add new rebroadcaster interface, use for background tx publish](https://github.com/lightning/bolts/pull/765)

### [LDK](https://github.com/lightningdevkit/rust-lightning)
- [#1977 BOLT12 deserialization fuzzers](https://github.com/lightningdevkit/rust-lightning/pull/1977)
- [#1988 Limit the number of pending un-funded inbound channel](https://github.com/lightningdevkit/rust-lightning/pull/1988)

### [Eclair](https://github.com/ACINQ/eclair)
- [#2596 Limit number of RBF attempts during dual funding](https://github.com/ACINQ/eclair/pull/2596)

### [Bitcoin-inquisition](https://github.com/bitcoin-inquisition/bitcoin)
- [#22 Add annex data carrier option behind -annexcarrier option](https://github.com/bitcoin-inquisition/bitcoin/pull/22)

### [BIP]
- [#1372: Add BIP MuSig2](https://github.com/bitcoin/bips/pull/1372)
- [#1421: Add OP_VAULT (BIP 345)](https://github.com/bitcoin/bips/pull/1421)

### [BOLT]
- [#765: Route Blinding](https://github.com/lightning/bolts/pull/765)

## New Releases
- [mempool.space v2.5.0](https://github.com/mempool/mempool/releases/tag/v2.5.0)
- [lnd v0.16.0-beta.rc1](https://github.com/lightningnetwork/lnd/releases/tag/v0.16.0-beta.rc1)
- [ldk v0.0.114](https://github.com/lightningdevkit/rust-lightning/releases/tag/v0.0.114)
- [core lightning v23.02.2](https://github.com/ElementsProject/lightning/releases/tag/v23.02.2)

## Miscellaneous
- [Validating Lightning Signer](https://vls.tech)
- [Lightning for Everyone in Any App](https://medium.com/breez-technology/lightning-for-everyone-in-any-app-lightning-as-a-service-via-the-breez-sdk-41d899057a1d)
