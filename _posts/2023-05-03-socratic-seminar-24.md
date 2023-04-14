---
layout: post
type: socratic
title: "Socratic Seminar #24"
meetup: https://www.meetup.com/bitdevsldn/events/292894936/
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
- [Seeking concept ACKs for transaction terminology BIP](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-April/021550.html)
- [RGB protocol announcement](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-April/021554.html)
- [Civ Kit: A Peer-to-Peer Electronic Market System](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-April/021556.html)
- [Proposal to Remove BIP35 P2P 'mempool' Message](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-April/021562.html)
- [Conjectures on solving the high interactivity issue in payment pools and channel factories](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-April/021560.html)
- [A new Bitcoin implementation integrated with Core Lightning](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-April/021566.html)
- [Vaults in the MATT framework](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-April/021588.html)
- [proposal: new opcode OP_ZKP to enable ZKP-based spending authorization](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-April/021592.html)
- [On adaptor security (in protocols)](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-April/021594.html)

#### [lightning-dev](https://lists.linuxfoundation.org/pipermail/lightning-dev)
- [Proposed changes to the splicing specification](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-March/003895.html)
- [Splice Lock Race Condition Solution](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-April/003903.html)

### Meetings
- [Bitcoin PR Review Club](https://bitcoincore.reviews)
  - #27255 MiniTapscript: port Miniscript to Tapscript: [part 1](https://bitcoincore.reviews/27255) and [part 2](https://bitcoincore.reviews/27255-2)
  - [#27039 Do not flush block to disk if it is already there](https://bitcoincore.reviews/27039)
  - [#27460 Add importmempool RPC](https://bitcoincore.reviews/27460)

### Optech
- [Newsletter #244](https://bitcoinops.org/en/newsletters/2023/03/29/), [audio recap](https://bitcoinops.org/en/podcast/2023/03/30/)
- [Newsletter #240](https://bitcoinops.org/en/newsletters/2023/04/05/), [audio recap](https://bitcoinops.org/en/podcast/2023/04/06/)
- [Newsletter #240](https://bitcoinops.org/en/newsletters/2023/04/12/), [audio recap](https://bitcoinops.org/en/podcast/2023/04/13/)
- [Newsletter #240](https://bitcoinops.org/en/newsletters/2023/04/19/), [audio recap](https://bitcoinops.org/en/podcast/2023/04/20/)
- [Newsletter #240](https://bitcoinops.org/en/newsletters/2023/04/26/), [audio recap](https://bitcoinops.org/en/podcast/2023/04/27/)

## CVEs and Research

### InfoSec
- [i2pd specific attack](https://github.com/PurpleI2P/i2pd/discussions/1918)
- [How to stop the onion denial (of service)](https://blog.torproject.org/stop-the-onion-denial/)
- [Network DDoS](https://status.torproject.org/issues/2022-06-09-network-ddos/)
- [Tor Project shares proposals to limit DDoS impact on Onion sites](https://www.bleepingcomputer.com/news/security/tor-project-shares-proposals-to-limit-ddos-impact-on-onion-sites/)
- [A First Take at Pow Over Introduction Circuits](https://gitlab.torproject.org/tpo/core/torspec/-/blob/main/proposals/327-pow-over-intro.txt?ref=nobsbitcoin.com)

## Pull Requests and repo updates
### [Bitcoin Core](https://github.com/bitcoin/bitcoin)
- [Add pool based memory resource](https://github.com/bitcoin/bitcoin/pull/25325)
- [addrman: Enable selecting addresses by network](https://github.com/bitcoin/bitcoin/pull/27214)
- [p2p: update hardcoded mainnet seeds for 25.x](https://github.com/bitcoin/bitcoin/pull/27488)
- [mempool: disallow txns under min relay fee, even in packages](https://github.com/bitcoin/bitcoin/pull/26933)
- [p2p: skip netgroup diversity of new connections for tor/i2p/cjdns](https://github.com/bitcoin/bitcoin/pull/27374)


### [LND](https://github.com/lightningnetwork/lnd)
- [watchtower: start using the DeleteSession message](https://github.com/lightningnetwork/lnd/pull/7069)
- [funding: add fundmax flag to OpenChannelRequest](https://github.com/lightningnetwork/lnd/pull/6903)

### [LDK](https://github.com/lightningdevkit/rust-lightning)
- [Only disable ~10 min after disconnect, rather than one](https://github.com/lightningdevkit/rust-lightning/pull/2198)

### [Eclair](https://github.com/ACINQ/eclair)
- [Add support for splices](https://github.com/ACINQ/eclair/pull/2584)

### [Core-Lightning](https://github.com/ElementsProject/lightning)
- [List runes](https://github.com/ElementsProject/lightning/pull/6124)
- [Zero fee htlc prep part #3: Block estimates, and the Return of RBF](https://github.com/ElementsProject/lightning/pull/6120)

### [Bitcoin-inquisition](https://github.com/bitcoin-inquisition/bitcoin)
- [Pseudo ephemeral anchors](https://github.com/bitcoin-inquisition/bitcoin/pull/23)

### [BOLT]
- [extension-bolt: taproot gossip](https://github.com/lightning/bolts/pull/1059)

## New Releases
- [libsecp256k1 v0.3.1 released](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-April/021553.html)

## Mining
- [Stratum V2 adds Job Negotiator](https://stratumprotocol.org/blog/stratumv2-jn-announcement/)
