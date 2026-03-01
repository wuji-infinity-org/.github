<div align="center">

# 无 极
### W U J I &nbsp; I N F I N I T Y

**A Digital Sovereignty OS — Own Your Identity, Data & AI**

*你的身份 · 你的数据 · 你的 AI · 你说了算*

<br>

[![Rust](https://img.shields.io/badge/Rust-2024_Edition-CE422B?style=flat-square&logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![License](https://img.shields.io/badge/License-AGPL_v3-4B8BBE?style=flat-square)](https://github.com/wuji-infinity-org/apeiron/blob/main/LICENSE)
[![Stage](https://img.shields.io/badge/Stage-Phase_1_·_Building-C9A84C?style=flat-square)](#roadmap)
[![Build in Public](https://img.shields.io/badge/Build_in_Public-Open-7C6BFF?style=flat-square)](https://twitter.com/wuji_infinity)

</div>

---

## What is Wuji? &nbsp;|&nbsp; 什么是无极？

**Wuji (无极)** is a Daoist concept meaning *"the boundless state before all things"* — the primordial source of infinite possibility.

We named our project Wuji because we believe your digital life should start from the same place: **unbounded. Sovereign. Truly yours.**

> *无极生太极，太极生两仪，万物归一。*
> *From the boundless, all things arise. To the One, all things return.*

The codebase is named **Apeiron** (ἄπειρον) — the ancient Greek philosopher Anaximander's equivalent concept: the infinite, primordial source of all things. Same idea. 2,600 years apart. Two civilizations. One insight.

---

## The Problem &nbsp;|&nbsp; 我们要解决的问题

Your digital life is **rented, not owned.**

```
Your social graph    → owned by the platform
Your health records  → scattered, inaccessible
Your AI assistant    → their model, your data, their profit
Your creative work   → one policy change from disappearing
```

No single solution today addresses all four dimensions simultaneously.
**Wuji does.**

---

## Six Core Components &nbsp;|&nbsp; 六大组件

| Component | Name | Role |
|-----------|------|------|
| 🔮 **灵境** | Atman · DID Identity | Self-sovereign identity — no platform can revoke it |
| 🤖 **灵识** | Manas · Local AI | Your AI runs local. Data never leaves your device. |
| 🛡️ **真身** | Dharma · ZK Proof | Prove who you are without revealing who you are |
| 🌐 **帝网** | Indra · P2P Network | No central server. No single point of failure. |
| 🔰 **守门人** | Dvarapala · Gatekeeper | You write the rules. The gatekeeper enforces them. |
| 🧩 **插件** | Sutra · WASM Rules | Code as law. Rules as auditable, sandboxed programs. |

---

## Architecture &nbsp;|&nbsp; 三层架构

```
┌─────────────────────────────────────────────┐
│  Meta-Plane · 元位面  ·  Digital Constitution │
│       Atman · Indra · Dharma                 │
│  Defines inviolable digital rights           │
└──────────────────┬──────────────────────────┘
                   │ constrains ↓
┌──────────────────▼──────────────────────────┐
│  Governance · 治理域  ·  Org Self-Rule        │
│       Dvarapala · Sutra · Manas              │
│  Families, teams & communities set rules    │
└──────────────────┬──────────────────────────┘
                   │ constrains ↓
┌──────────────────▼──────────────────────────┐
│  Application · 应用域  ·  Life Scenarios      │
│    Healthcare · Education · Finance · Art    │
│  Apps must comply with layers above          │
└─────────────────────────────────────────────┘
```

---

## Tech Stack &nbsp;|&nbsp; 技术栈

```rust
// Your digital sovereignty, in code
let wuji = Wuji::builder()
    .identity(Did::new(KeyType::Ed25519))          // 灵境 — W3C DID
    .network(IndraNode::with(Transport::Libp2p))   // 帝网 — libp2p
    .privacy(ZkProof::new(Circuit::Groth16))       // 真身 — ZK-SNARKs
    .ai(LocalAgent::run_on_device())               // 灵识 — Local LLM
    .gatekeeper(Dvarapala::default_deny())         // 守门人 — Gatekeeper
    .rules(WasmPlugin::sandboxed())                // 插件 — WASM
    .build()?;
```

| Layer | Technology | Why |
|-------|-----------|-----|
| Language | **Rust 2024** | Memory safety is non-negotiable for identity infra |
| P2P | **libp2p** | Battle-tested — same layer as Ethereum & IPFS |
| Identity | **W3C DID** | International standard, not a proprietary format |
| Communication | **DIDComm v2** | End-to-end encrypted, identity-aware messaging |
| Privacy | **ZK-SNARKs** | Prove things without revealing them |
| Rules | **WASM (wasmtime)** | Sandboxed, auditable, user-controlled |
| AI | **Local LLM** | On-device inference — data never leaves |

---

## Current Status &nbsp;|&nbsp; 当前进度

**Phase 1 · Foundation** `[████░░░░░░]` 40%

```
✅  灵境 · Atman      DID identity core             in progress
✅  帝网 · Indra      P2P network node              in progress
⬜  守门人 · Dvara    Data access gatekeeper        planned
⬜  插件 · Sutra      WASM rule engine              planned
⬜  真身 · Dharma     ZK proof layer                planned
⬜  灵识 · Manas      Local AI integration          planned
```

> Building in public from day 0. Every decision, every failure, every milestone — documented openly.

---

## Follow the Journey &nbsp;|&nbsp; 关注进展

<div align="center">

| Platform | Link | Content |
|----------|------|---------|
| 𝕏 Twitter | [@wuji_infinity](https://twitter.com/wuji_infinity) | Weekly dev logs · Build in Public |
| 📰 Newsletter | [Substack](https://wuji-infinity.substack.com) | Deep dives · Digital sovereignty |
| ☕ Support | [爱发电](https://afdian.com/a/wuji-infinity) | Back the project |
| 💬 公众号 | 无极INFINITY | 中文深度内容 |

</div>

---

<div align="center">

*"无极生太极 — From the boundless, sovereignty begins."*

**[⭐ Star the Repo](https://github.com/wuji-infinity-org/apeiron)** &nbsp;·&nbsp; **[Read the Docs](https://github.com/wuji-infinity-org/apeiron/tree/main/docs)** &nbsp;·&nbsp; **[Follow @wuji_infinity](https://twitter.com/wuji_infinity)**

</div>
