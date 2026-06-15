<p align="center">
  <a href="https://bloom.directory">
    <img src="https://raw.githubusercontent.com/bloom-directory/.github/main/assets/banner.png" alt="/bloom" width="900">
  </a>
</p>

[Bloom](https://bloom.directory) is building file-native infrastructure for trusted human-agent software collaboration.

The core interface is a `/bloom` namespace: agents read state like files, stage actions by writing to files, and leave humans with explicit plans to review before anything sensitive is signed or deployed. Under the hood, Bloom combines verifiable execution, content-addressed modules, human-defined invariants, staking, governance, and continuous verification.

This GitHub organization hosts Bloom's open-source protocol work, developer tooling, research prototypes, and production surfaces.

Among other things, we are building:

* [Bloom](https://github.com/bloom-directory/bloom): an agentic Ethereum wallet exposed as a virtual filesystem, with chain views, wallet action staging, and reviewable transaction plans.
* [Bloom Docs](https://github.com/bloom-directory/docs): user-facing documentation, quickstarts, and the canonical setup path for agents using Bloom.
* [embednfs](https://github.com/bloom-directory/embednfs): an embeddable Rust NFSv4.1 server for exposing application state through ordinary filesystem clients.
* [Bloom research](https://docs.bloom.directory): research and implementation notes around VFS-first agent interfaces, contract drift detection, verifiable package claims, zk build attestations, and petal execution.
* [Bloom whitepaper](https://bloom.directory): the protocol design for trusted collaboration between humans and increasingly autonomous software agents.

We care about interfaces that are legible to both people and agents: files over opaque dashboards, deterministic artifacts over vibes, and explicit review boundaries over silent automation.

Start with the [docs](https://docs.bloom.directory), the [agent setup skill](https://bloom.directory/SKILL.md), or the public [Bloom repository](https://github.com/bloom-directory/bloom).
