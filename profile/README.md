<p align="center">
  <a href="https://bloom.directory">
    <img src="../assets/banner.png" alt="/bloom">
  </a>
  <strong>The programmable financial harness for AI agents.</strong>
</p>

[Bloom](https://bloom.directory) gives agents a programmable filesystem for financial work: read state, compose tools, and stage actions using ordinary files and shell pipelines. Today, those workflows run on EVM-compatible chains and native Solana through self-custodial wallets.

The core interface is the mounted `/bloom` namespace. Reads expose chain and wallet state; writes stage transaction intents with reviewable plans. Agents can compose queries, encoding helpers, simulations, watches, and transaction staging without handling private keys. **Petals** extend the filesystem with protocol and workflow capabilities under the same policy, approval, and signing boundaries.

Authority is enforced by separate services: **Machine** presents the filesystem and executes work, **Broker** evaluates policy and manages human approval, and **Signer** holds private keys and produces signatures. **Sealed Approvals** bind signing authority to exact payloads or tightly scoped Petal operations, with limits and expiry. Approval does not broadcast a transaction by itself.

We're building towards a **general purpose human-in-the-loop architecture**: software capabilities agents can inspect and compose, with human-defined policy and explicit authorization enforced outside the agent. Financial workflows are the starting point, where custody, approval, and execution boundaries must be concrete.

* [Bloom](https://github.com/bloom-directory/bloom): the filesystem runtime, financial tooling, Petal interfaces, and agent setup skill.
* [Bloom Docs](https://docs.bloom.directory): setup, filesystem workflows, security boundaries, and developer documentation ([source](https://github.com/bloom-directory/docs)).
