---
title: Backup Wallet
---

#### Seeds and Public Keys
There are two components to your wallet that you need to backup to guarantee recovery:
* **Seeds** (BIP39 phrases) - these are your 12-24 phrases. You only need to have `m` (of your total `n`) seeds to recover your funds. These should be guarded very carefully as anyone who gets access to these can steal your bitcoin! Seeds should be stored in different locations.
* **Extended Public Keys** and related configuration settings (bip32 paths, quorum settings, and master public key fingerprints) - one confusing thing about multisig is that you need *all* of your exenteded public keys (and related configuration settings) in order to be able to recover your funds. These do not need to be guarded nearly as carefully, as anyone who gets access to this can only see which bitcoin addresses belong to you (but cannot spend from them). For non-expert users, we recommend making *lots* of redundant copies of this, and storing a copy of *all* extended public keys with *each* individual seed.

{% comment %}TODO: auto-gen this TOC somehow?{% endcomment %}
## Table of Contents
* [Backup Seeds Instructions](/backup-wallet/seeds)
* [Backup Extended Public Keys](/backup-wallet/public-keys)

{% include advanced_config.md %}