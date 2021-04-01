---
title: "RiB Newsletter #22"
description: "#22 - March 2021"
date: 2021-03-31
slug: "/"
categories:
  - "newsletters"
summary: ""
---

Welcome to the #22 edition of Rust in Blockchain,
the chillest newsletter about the chillest tech.
[Previous: #21](/newsletters/more-rust-and-blockchains/).

&nbsp;

## Thanks

Thanks to contributors:
[Ernest Kissiedu][contributor-ek],
[Max Wegman][contributor-mw],
[NiklasHusten][contributor-nh],
[Brian Anderson][contributorba], and [Aimee Zhu][contributoraz].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects. 
If you follow a particular project, or otherwise find information 
that is beneficial to the Rust & blockchain community, 
please contribute to the next issue
by submitting a PR to the [#23 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[contributor-ek]: https://github.com/ernestkissiedu
[contributor-mw]: https://github.com/mastermaxy
[contributor-nh]: https://github.com/NiklasHusten
[contributorba]: https://github.com/brson
[contributoraz]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

&nbsp;


## Interesting Things

#### Blog Posts

- [Further adventures with Substrate and Ink](https://brson.github.io/2021/03/09/further-adventures-with-substrate-and-ink)
- [The Most Important Scarce Resource is Legitimacy](https://vitalik.ca/general/2021/03/23/legitimacy.html)

#### Papers

- [ESCORT: Ethereum Smart COntRacTs Vulnerability Detection using Deep Neural Network and Transfer Learning](https://arxiv.org/abs/2103.12607)
- [Non-interactive half-aggregation of EdDSA and variants of Schnorr signatures](https://eprint.iacr.org/2021/350)
- [Multiparty Computation with Covert Security and Public Verifiability](https://eprint.iacr.org/2021/366)
- [Latus Incentive Scheme: Enabling Decentralization in Blockchains based on Recursive SNARKs](https://eprint.iacr.org/2021/399)
- [Bolt-Dumbo Transformer: Asynchronous Consensus As Fast As Pipelined BFT](https://arxiv.org/abs/2103.09425)
- Revised [Zexe: Enabling Decentralized Private Computation](https://eprint.iacr.org/2018/962)


#### Projects

- [GhostCell](http://plv.mpi-sws.org/rustbelt/ghostcell/).
  Its paper: [GhostCell: Separating Permissions from Data in Rust](http://plv.mpi-sws.org/rustbelt/ghostcell/paper.pdf)
- [Kamu Data](https://github.com/kamu-data/kamu-cli).
  Tool for decentralized exchange and transformation of semi-structured data.
- [clvm-rs](https://github.com/Chia-Network/clvm_rs).
  Rust implementation of clvm.

&nbsp;

## Most Active in March

[Parity](https://github.com/paritytech):
356 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6]), 126 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5]), 
110 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6])

[Solana](https://github.com/solana-labs/solana):
404 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]), 35 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
51 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[Diem](https://github.com/diem):
189 merged PRs ([1][diem-merged-prs-1]), 12 closed issues ([1][diem-closed_issues-1]), 
19 open issues ([1][diem-open_issues-1])


&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

54 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2]), 24 closed issues ([1][aleo-closed_issues-1]), 
23 open issues ([1][aleo-open_issues-1])

[aleo-merged-prs-1]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[aleo-merged-prs-2]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[aleo-closed_issues-1]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[aleo-open_issues-1]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31

- Blog:
  - [zkCloud: Decentralized Private Computing](https://www.aleo.org/post/zkcloud)
  - [Zero Knowledge Primitives by Aleo](https://www.aleo.org/post/zero-knowledge-primitives-by-aleo)
- PR: [[Feature, Compiler] Adds constant inputs ](https://github.com/AleoHQ/leo/pull/761) by [@damirka](https://github.com/damirka)
- PR: [Feature/canonicalization before asg](https://github.com/AleoHQ/leo/pull/793) by [@gluax](https://github.com/gluax)

#### [COMIT](https://github.com/comit-network)

105 merged PRs ([1][comit-merged-prs-1], [2][comit-merged-prs-2]), 35 closed issues ([1][comit-closed_issues-1]), 
23 open issues ([1][comit-open_issues-1], [2][comit-open_issues-2])

[comit-merged-prs-1]: https://github.com/comit-network/comit-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[comit-merged-prs-2]: https://github.com/comit-network/xmr-btc-swap/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[comit-closed_issues-1]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[comit-open_issues-1]: https://github.com/comit-network/comit-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31
[comit-open_issues-2]: https://github.com/comit-network/xmr-btc-swap/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31

- PR: [Monero rpc installer for windows](https://github.com/comit-network/xmr-btc-swap/pull/253) by [@rishflab](https://github.com/rishflab)
- PR: [Add asb to release including ARM build](https://github.com/comit-network/xmr-btc-swap/pull/311) by [@da-kami](https://github.com/da-kami)

#### [Concordium](https://github.com/Concordium)

9 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3]),
0 closed issues, 0 open issues

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-contracts-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31

- News: [Concordium Annouce their Contribution to the Rust Ecosystem; The DevX Initiative](https://medium.com/concordium/the-devx-initiative-by-concordium-f0e2550f8bc3)
- PR: [CB-1203: Contract and receive names](https://github.com/Concordium/concordium-contracts-common/pull/14) by [@Bargsteen](https://github.com/Bargsteen)
- PR: [CB-1203: Ergonomic send](https://github.com/Concordium/concordium-rust-smart-contracts/pull/25) by [@Bargsteen](https://github.com/Bargsteen)

#### [Conflux](https://github.com/Conflux-Chain)

31 merged PRs ([1][conflux-merged-prs-1]), 11 closed issues ([1][conflux-closed_issues-1]), 
6 open issues ([1][conflux-open_issues-1])

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[conflux-closed_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[conflux-open_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31

- PR: [Fix mining author](https://github.com/Conflux-Chain/conflux-rust/pull/2087) by [@peilun-conflux](https://github.com/peilun-conflux)
- PR: [Create StateTrait for the new state implementation.](https://github.com/Conflux-Chain/conflux-rust/pull/2095) by [@yangzhe1990](https://github.com/yangzhe1990)

#### [Diem](https://github.com/diem)
189 merged PRs ([1][diem-merged-prs-1]), 12 closed issues ([1][diem-closed_issues-1]), 
19 open issues ([1][diem-open_issues-1])

[diem-merged-prs-1]: https://github.com/diem/diem/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[diem-closed_issues-1]: https://github.com/diem/diem/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[diem-open_issues-1]: https://github.com/diem/diem/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31

- PR: [[types] add script function as a new txn payload](https://github.com/diem/diem/pull/7580) by [@mengxu-fb](https://github.com/mengxu-fb)
- PR: [initial off-chain api spec](https://github.com/diem/diem/pull/8059) by [@davidiw](https://github.com/davidiw)

#### [Elrond](https://github.com/ElrondNetwork)

40 merged PRs ([1][elrond-merged-prs-1], [2][elrond-merged-prs-2]), 1 closed issues ([1][elrond-closed_issues-1]), 
0 open issues

[elrond-merged-prs-1]: https://github.com/ElrondNetwork/sc-delegation-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[elrond-merged-prs-2]: https://github.com/ElrondNetwork/elrond-wasm-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[elrond-closed_issues-1]: https://github.com/ElrondNetwork/elrond-wasm-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31

- PR: [Erc1155 marketplace](https://github.com/ElrondNetwork/elrond-wasm-rs/pull/131) by [@dorin-iancu](https://github.com/dorin-iancu)
- PR: [egld-esdt-swap contract, ESDT issue/mint](https://github.com/ElrondNetwork/elrond-wasm-rs/pull/160) by [@andrei-marinica](https://github.com/andrei-marinica)

#### [Fluence](https://github.com/fluencelabs)

24 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4]),
0 closed issues, 0 open issues

[fluence-merged-prs-1]: https://github.com/fluencelabs/fluence/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[fluence-merged-prs-2]: https://github.com/fluencelabs/fce/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[fluence-merged-prs-3]: https://github.com/fluencelabs/aquamarine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[fluence-merged-prs-4]: https://github.com/fluencelabs/rust-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31

- PR: [Basic validator for variables](https://github.com/fluencelabs/aquamarine/pull/76) by [@michaelvoronov](https://github.com/michaelvoronov)
- PR: [use hash for blueprint ids](https://github.com/fluencelabs/fluence/pull/1048) by [@DieMyst](https://github.com/DieMyst)

#### [Golem](https://github.com/golemfactory)

64 merged PRs ([1][golem-merged-prs-1], [2][golem-merged-prs-2]), 33 closed issues ([1][golem-closed_issues-1]), 
25 open issues ([1][golem-open_issues-1])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[golem-merged-prs-2]: https://github.com/golemfactory/ya-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31

- PR: [upgrade erc20](https://github.com/golemfactory/yagna/pull/1157) by [@maaktweluit](https://github.com/maaktweluit)
- PR: [we have a new yacn server](https://github.com/golemfactory/yagna/pull/1121) by [@etam](https://github.com/etam)

#### [Grin](https://github.com/mimblewimble/grin)

30 merged PRs ([1][grin-merged-prs-1]), 8 closed issues ([1][grin-closed_issues-1]), 
10 open issues ([1][grin-open_issues-1])

[grin-merged-prs-1]: https://github.com/mimblewimble/grin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[grin-closed_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[grin-open_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31

- PR: [enhance comment describing how a pow is hashed](https://github.com/mimblewimble/grin/pull/3623) by [@bladedoyle](https://github.com/bladedoyle)
- PR: [Defork croaring](https://github.com/mimblewimble/grin/pull/3596) by [@trevyn](https://github.com/trevyn)

#### [Holochain](https://github.com/holochain/)

40 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2], [3][holochain-merged-prs-3]), 2 closed issues ([1][holochain-closed_issues-1], [2][holochain-closed_issues-2]), 
6 open issues ([1][holochain-open_issues-1])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[holochain-merged-prs-2]: https://github.com/holochain/elemental-chat/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[holochain-merged-prs-3]: https://github.com/holochain/lair/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[holochain-closed_issues-1]: https://github.com/holochain/holochain-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[holochain-closed_issues-2]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31

- News: [Dev Pulse 92 Dev Tools in the Works](https://blog.holochain.org/dev-tools-in-the-works/)
- Blog:
  - [How rrDHT Works: A Tech Deep Dive](https://blog.holochain.org/how-rrdht-works-a-tech-deep-dive/)
  - [Decentralized Next-level Collaboration Apps with Syn](https://blog.holochain.org/decentralized-next-level-collaboration-apps-with-syn/)  
- PR: [[B-03964] Arc length targeting](https://github.com/holochain/holochain/pull/666) by [@freesig](https://github.com/freesig)
- PR: [MDNS crate](https://github.com/holochain/holochain/pull/663) by [@ddd-mtl](https://github.com/ddd-mtl)

#### [Interledger](https://github.com/interledger-rs)

6 merged PRs ([1][interledger-merged-prs-1]), 3 closed issues ([1][interledger-closed_issues-1]), 
2 open issues ([1][interledger-open_issues-1])

[interledger-merged-prs-1]: https://github.com/interledger-rs/interledger-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[interledger-closed_issues-1]: https://github.com/interledger-rs/interledger-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[interledger-open_issues-1]: https://github.com/interledger-rs/interledger-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31

- PR: [Bytes 05 upgrade](https://github.com/interledger-rs/interledger-rs/pull/690) by [@koivunej](https://github.com/koivunej)

#### [Lighthouse](https://github.com/sigp/lighthouse)

1 merged PRs ([1][lighthouse-merged-prs-1]), 24 closed issues ([1][lighthouse-closed_issues-1]), 
12 open issues ([1][lighthouse-open_issues-1], [2][lighthouse-open_issues-2])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31
[lighthouse-open_issues-2]: https://github.com/sigp/discv5/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31

- News: [New Eth2 Lighthouse release](https://twitter.com/sigp_io/status/1376780503764754435)
- Blog: [Who’s who in eth2: Paul Hauner from Sigma Prime](https://bisontrails.co/eth2/paul-hauner/)
- PR: [Update stable to v1.2.0](https://github.com/sigp/lighthouse/pull/2253) by [@michaelsproul](https://github.com/michaelsproul)

#### [MobileCoin](https://github.com/mobilecoinfoundation)

21 merged PRs ([1][mobilecoin-merged-prs-1]), 4 closed issues ([1][mobilecoin-closed_issues-1]), 
2 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[mobilecoin-closed_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31

- PR: [MCC-2276 Reference implementation of BIP-39 + SLIP-0010 Key Derivation ](https://github.com/mobilecoinfoundation/mobilecoin/pull/771) by [@jcape](https://github.com/jcape)
- PR: [Add slam tool to consensus server repo](https://github.com/mobilecoinfoundation/mobilecoin/pull/733) by [@garbageslam](https://github.com/garbageslam)

#### [NEAR](https://github.com/nearprotocol/nearcore)

127 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3], [4][near-merged-prs-4]), 51 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3]), 
30 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3])

[near-merged-prs-1]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[near-merged-prs-2]: https://github.com/near/core-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[near-merged-prs-3]: https://github.com/near/near-evm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[near-merged-prs-4]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[near-closed_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[near-closed_issues-2]: https://github.com/near/near-evm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[near-closed_issues-3]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[near-open_issues-1]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31
[near-open_issues-2]: https://github.com/near/borsh/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31
[near-open_issues-3]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31

- News:
  - [Well hello, NEAR Academy!](https://near.org/blog/well-hello-near-academy/)
  - [Berry Cards: a DeFi NFT Marketplace for Pixel Art](https://near.org/blog/berry-cards/)
  - [Octopus builds on NEAR](https://near.org/blog/octopus-network-partners-with-near/)
- PR: [feat(contract-standards): Adding near-contract-standards library and more tools](https://github.com/near/near-sdk-rs/pull/275) by [@ilblackdragon](https://github.com/ilblackdragon)
- PR: [refactor(jsonrpc): Add structured errors to query method in ViewClient and RPC](https://github.com/near/nearcore/pull/3944) by [@khorolets](https://github.com/khorolets)
- PR: [feat(chain): Epoch Sync / GC Headers skeleton](https://github.com/near/nearcore/pull/4023) by [@Kouprin](https://github.com/Kouprin)

#### [Nervos](https://github.com/nervosnetwork)

48 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3]), 0 closed issues, 
3 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[nervos-merged-prs-3]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31
[nervos-open_issues-2]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31

- News: [Nervos Unveils 2021 Roadmap at Town Hall](https://medium.com/nervosnetwork/nervos-unveils-2021-roadmap-at-town-hall-e9f02b957096)
- PR: [feat: metricize network traffic](https://github.com/nervosnetwork/ckb/pull/2509) by [@keroro520](https://github.com/keroro520)
- PR: [B extension](https://github.com/nervosnetwork/ckb-vm/pull/108) by [@mohanson](https://github.com/mohanson)

#### [Oasis](https://github.com/oasislabs)

1 merged PRs ([1][oasis-merged-prs-1]),
0 closed issues, 1 open issues ([1][oasis-open_issues-1])

[oasis-merged-prs-1]: https://github.com/oasislabs/oasis-ethwasi-runtime/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[oasis-open_issues-1]: https://github.com/oasisprotocol/deoxysii-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31

- PR: [Update to oasis-core 21.0.1](https://github.com/oasislabs/oasis-ethwasi-runtime/pull/1021) by [@ptrus](https://github.com/ptrus)

#### [Parity](https://github.com/paritytech)

356 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6]), 126 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5]), 
110 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[parity-merged-prs-3]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[parity-merged-prs-4]: https://github.com/paritytech/wasmi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[parity-merged-prs-5]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[parity-merged-prs-6]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[parity-closed_issues-3]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[parity-closed_issues-4]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[parity-closed_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31
[parity-open_issues-3]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31
[parity-open_issues-4]: https://github.com/paritytech/wasmi/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31
[parity-open_issues-5]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31
[parity-open_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31

- Blog: [Polkadot Bridges - Connecting the Polkadot Ecosystem with External Networks](https://polkadot.network/polkadot-bridges-connecting-the-polkadot-ecosystem-with-external-networks/)
- PR: [Storage chains: indexing, renewals and reference counting](https://github.com/paritytech/substrate/pull/8265) by [@arkpar](https://github.com/arkpar)
- PR: [Decouple Staking and Election - Part 2.1: Unleash Multi Phase](https://github.com/paritytech/substrate/pull/8113) by [@kianenigma](https://github.com/kianenigma)
- PR: [Implement `fungible::*` for Balances](https://github.com/paritytech/substrate/pull/8454) by [@gavofyork](https://github.com/gavofyork)

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

41 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3], [4][rust_bitcoin-merged-prs-4]), 7 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2]), 
9 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3], [4][rust_bitcoin-open_issues-4])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[rust_bitcoin-merged-prs-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31
[rust_bitcoin-open_issues-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31

- PR: [MPP on the router side](https://github.com/rust-bitcoin/rust-lightning/pull/646) by [@naumenkogs](https://github.com/naumenkogs)
- PR: [Process monitor update events in block_[dis]connected asynchronously](https://github.com/rust-bitcoin/rust-lightning/pull/808) by [@TheBlueMatt](https://github.com/TheBlueMatt)

#### [Rust Ethereum](https://github.com/rust-ethereum)

8 merged PRs ([1][rust-ethereum-merged-prs-1]), 4 closed issues ([1][rust-ethereum-closed_issues-1]), 
3 open issues ([1][rust-ethereum-open_issues-1])

[rust-ethereum-merged-prs-1]: https://github.com/rust-ethereum/ethabi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[rust-ethereum-closed_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[rust-ethereum-open_issues-1]: https://github.com/rust-ethereum/ethabi/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31

- PR: [Release v14.0.0](https://github.com/rust-ethereum/ethabi/pull/219) by [@vkgnosis](https://github.com/vkgnosis)
- PR: [Re-export ethereum-types](https://github.com/rust-ethereum/ethabi/pull/218) by [@vkgnosis](https://github.com/vkgnosis)

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

5 merged PRs ([1][secret_network-merged-prs-1]), 0 closed issues, 
1 open issues ([1][secret_network-open_issues-1])

[secret_network-merged-prs-1]: https://github.com/enigmampc/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[secret_network-open_issues-1]: https://github.com/enigmampc/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31

- PR: [Update install_cli.md](https://github.com/enigmampc/SecretNetwork/pull/733) by [@Steven-Chang](https://github.com/Steven-Chang)
- PR: [SSD Update](https://github.com/enigmampc/SecretNetwork/pull/731) by [@moonstash](https://github.com/moonstash)

#### [Solana](https://github.com/solana-labs/solana)

404 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2]), 35 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]), 
51 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31

- PR: [CRUD program: create / update / delete](https://github.com/solana-labs/solana-program-library/pull/1226) by [@joncinque](https://github.com/joncinque)
- PR: [Implement mnemonic support for solana-keygen grind (solana-labs#9325)](https://github.com/solana-labs/solana/pull/16108) by [@bji](https://github.com/bji)

#### [Spacemesh](https://github.com/spacemeshos)

5 merged PRs ([1][spacemesh-merged-prs-1]), 21 closed issues ([1][spacemesh-closed_issues-1]), 
26 open issues ([1][spacemesh-open_issues-1])

[spacemesh-merged-prs-1]: https://github.com/spacemeshos/svm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[spacemesh-closed_issues-1]: https://github.com/spacemeshos/go-spacemesh/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[spacemesh-open_issues-1]: https://github.com/spacemeshos/go-spacemesh/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31

- PR: [Plugging-in rocksdb](https://github.com/spacemeshos/svm/pull/225) by [@YaronWittenstein](https://github.com/YaronWittenstein)
- PR: [WIP: Adding the `verify` stage](https://github.com/spacemeshos/svm/pull/223) by [@YaronWittenstein](https://github.com/YaronWittenstein)
- PR: [Refactoring the Runtime component](https://github.com/spacemeshos/svm/pull/224) by [@YaronWittenstein](https://github.com/YaronWittenstein)

#### [Zcash](https://github.com/zcash)

102 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3]), 40 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3]), 
56 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[zcash-merged-prs-3]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[zcash-closed_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31
[zcash-open_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31
[zcash-open_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31

- News:
  - [NU5 Proposed Features](https://electriccoin.co/blog/nu5-proposed-features/)
  - [https://electriccoin.co/blog/ecc-transparency-report-for-q3-2020/](https://electriccoin.co/blog/ecc-transparency-report-for-q3-2020/)
  - [The Zcash Foundation has Finished an Audit of FROST](https://www.zfnd.org/blog/frost-audit/)
  - Zcash Developers Update [3-26](https://www.zcashcommunity.com/2021/03/27/zcash-developers-update-3-26-2021/),
  [3-19](https://www.zcashcommunity.com/2021/03/21/zcash-developers-update-3-19-2021/),
  [3-12](https://www.zcashcommunity.com/2021/03/12/zcash-developers-update-3-12-2021/),
  [3-5](https://www.zcashcommunity.com/2021/03/05/zcash-developers-update-3-5-2021/)
- PR: [V5 transaction rfc](https://github.com/ZcashFoundation/zebra/pull/1886) by [@oxarbitrage](https://github.com/oxarbitrage)
- PR: [Refactor Sapling data and use it in V4](https://github.com/ZcashFoundation/zebra/pull/1946) by [@oxarbitrage](https://github.com/oxarbitrage)

#### [zkSync](https://github.com/matter-labs/zksync)

1 merged PRs ([1][zksync-merged-prs-1]), 3 closed issues ([1][zksync-closed_issues-1]), 
8 open issues ([1][zksync-open_issues-1])

[zksync-merged-prs-1]: https://github.com/matter-labs/zksync/pulls?q=is%3Apr+is%3Aclosed+merged%3A2021-03-01..2021-03-31
[zksync-closed_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aclosed+closed%3A2021-03-01..2021-03-31
[zksync-open_issues-1]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aopen+created%3A2021-03-01..2021-03-31

- PR: [a fix in the batch fee check](https://github.com/matter-labs/zksync/pull/290) by [@lukasz-glen](https://github.com/lukasz-glen)


&nbsp;

## Events

<!--

May 1-2 | Online

[Event Sample](https://event.sample)

-->

May 20 | Online

[Polkadot Decoded](https://decoded.polkadot.network/)


&nbsp;

## Careers

<!--
Company name | Location A, B, Remote
- [Job 1](https://job.one)
- [Job 2](https://job.two)
-->

Chainflip | Berlin, Remote 
- [Full Stack DeFi Engineer](https://angel.co/company/chainflip/jobs/1122890-full-stack-defi-engineer)
- [Rust / C++ Backend Engineer](https://angel.co/company/chainflip/jobs/1162345-rust-c-backend-engineer)

Matter Labs | Berlin, Kiev, Remote
- [Senior Software Engineer (Rust)](https://www.notion.so/Senior-Software-Engineer-Rust-162f87f441214eb39619f83bdd9b3073)

Parity | Berlin & Remote
- [Blockchain Node Developer (Rust)](https://grnh.se/a070a3c83us)
- [Rust Performance Engineer](https://grnh.se/122d55873us)
- [Many other Rust blockchain engineering roles](https://www.parity.io/jobs/)

More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[#23 draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain

