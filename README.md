# sidestr:dreamlab — mirror

The DreamLab root sidechain beside Bitcoin testnet4 (`parent: tbtc4`), a [sidestr](https://github.com/sidestr/spec) chain: level 1, one signer, coins with no value.

This repository is a **mirror** in the sense of SPEC §11: `chain.json` (the sealed document; its `signer` is the key that announces the tip on Nostr as kind 33333), `blocks.dat` (`[u32 height][u32 size][block]`) and `blocks.json` (the index). Served by GitHub Pages at `https://dreamlab-ai.github.io/sidestr-dreamlab` with open CORS and Range requests.

Explorer: `https://sidestr.com/explorer/?chain=sidestr:dreamlab` · Directory: `https://play-grounds.github.io/sidestr/` · Source of the chain document: [agentbox `config/sidechain/dreamlab`](https://github.com/DreamLab-AI/agentbox/tree/main/config/sidechain/dreamlab).
