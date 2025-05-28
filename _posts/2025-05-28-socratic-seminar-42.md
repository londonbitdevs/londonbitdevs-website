---
layout: post
type: socratic
title: "Socratic Seminar #42"
meetup: https://www.meetup.com/bitdevsldn/events/307818818
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
- [Dust Expiry: Clean the UTXO set from spam](https://delvingbitcoin.org/t/dust-expiry-clean-the-utxo-set-from-spam/1707)
- [Withdrawing OP\_VAULT (BIP-345)](https://delvingbitcoin.org/t/withdrawing-op-vault-bip-345/1670)
- [Addressing community concerns and objections regarding my recent proposal to relax Bitcoin Core's standardness limits on OP\_RETURN outputs](https://delvingbitcoin.org/t/addressing-community-concerns-and-objections-regarding-my-recent-proposal-to-relax-bitcoin-cores-standardness-limits-on-op-return-outputs/1697)
- [On the possibility of evil covenants and implications for soft fork proposals](https://delvingbitcoin.org/t/on-the-possibility-of-evil-covenants-and-implications-for-soft-fork-proposals/1703)
- [Latency and Privacy in Lightning](https://delvingbitcoin.org/t/latency-and-privacy-in-lightning/1723)
- [Mitigating Channel Depletion in the Lightning Network: A Survey of Potential Solutions](https://delvingbitcoin.org/t/mitigating-channel-depletion-in-the-lightning-network-a-survey-of-potential-solutions/1640)
- [Bitcointap: an strace-like tool for bitcoin ebpf USDT tracepoints](https://delvingbitcoin.org/t/bitcointap-an-strace-like-tool-for-bitcoin-ebpf-usdt-tracepoints/1694)

### Mailing Lists
#### [bitcoindev](https://groups.google.com/g/bitcoindev)
- [Removing checkpoints in Bitcoin Core v30](https://groups.google.com/g/bitcoindev/c/qyId8Yto45M)
- [Introducing Hourglass](https://groups.google.com/g/bitcoindev/c/zmg3U117aNc)
- [The Tragic Tale of BIP30](https://groups.google.com/g/bitcoindev/c/aqHRfa0UWFo)
- [Censorship Resistant Transaction Relay - Taking out the garbage(man)](https://groups.google.com/g/bitcoindev/c/bmV1QwYEN4k)


### Meetings
- [Bitcoin PR Review Club](https://bitcoincore.reviews)
  - [#31981 Add checkBlock() to Mining interface](https://bitcoincore.reviews/31981)
  - [#31375 Add bitcoin wrapper executable](https://bitcoincore.reviews/31375)
  - [#32317 Separate UTXO set access from validation functions](https://bitcoincore.reviews/32317)

### Optech
- [Newsletter #352](https://bitcoinops.org/en/newsletters/2025/05/02/), [audio recap](https://bitcoinops.org/en/podcast/2025/05/06/)
- [Newsletter #353](https://bitcoinops.org/en/newsletters/2025/05/09/), [audio recap](https://bitcoinops.org/en/podcast/2025/05/13/)
- [Newsletter #354](https://bitcoinops.org/en/newsletters/2025/05/16/), [audio recap](https://bitcoinops.org/en/podcast/2025/05/20/)
- [Newsletter #355](https://bitcoinops.org/en/newsletters/2025/05/23/), [audio recap](https://bitcoinops.org/en/podcast/2025/05/27/)

## CVEs and Research
### Research
- [Bitcoin and Quantum Computing: Current Status and Future Directions](https://chaincode.com/bitcoin-post-quantum.pdf)

### InfoSec
- [CVE-2024-52919 - Remote crash due to addr message spam (part 2)](https://bitcoincore.org/en/2025/04/28/disclose-cve-2024-52919/)

## Pull Requests and repo updates
### [Bitcoin Core](https://github.com/bitcoin/bitcoin)
- [multiprocess: Add bitcoin wrapper executable](https://github.com/bitcoin/bitcoin/pull/31375)
- [cluster mempool: add txgraph diagrams/mining/eviction](https://github.com/bitcoin/bitcoin/pull/31444)
- [Remove the legacy wallet and BDB dependency](https://github.com/bitcoin/bitcoin/pull/28710)
- [miner: timelock the coinbase to the mined block's height](https://github.com/bitcoin/bitcoin/pull/32155)
- [rpc: Undeprecate rpcuser/rpcpassword, store all credentials hashed in memory](https://github.com/bitcoin/bitcoin/pull/32423)
- [policy: uncap datacarrier by default](https://github.com/bitcoin/bitcoin/pull/32406)

### [BIPs](https://github.com/bitcoin/bips)
- [BIP 54: Consensus Cleanup](https://github.com/bitcoin/bips/pull/1800)
- [BIP 53: Disallow 64-byte transactions](https://github.com/bitcoin/bips/pull/1760)
- [BIP 443: OP\_CHECKCONTRACTVERIFY](https://github.com/bitcoin/bips/pull/1793)
- [BIP-345: withdraw](https://github.com/bitcoin/bips/pull/1848)

## New Releases
- [tx-pigeon](https://github.com/stutxo/tx-pigeon)
- [Simplicity merged in elements 23.3](https://github.com/ElementsProject/elements/releases/tag/elements-23.3.0)

## Miscellaneous
- [Fix improper parsing of transaction with some nVersion](https://github.com/MetacoSA/NBitcoin/pull/1269)
- [Block to roll out bitcoin payments on Square](https://block.xyz/inside/block-to-roll-out-bitcoin-payments-on-square)
