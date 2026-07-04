<div align="center">

# 👋 Hi, I'm lightless

### Security Engineer · Hacker · Systems Builder

<p>
  <a href="https://lightless.me/">
    <img src="https://img.shields.io/badge/Blog-lightless.me-111111?style=flat-square&logo=ghost&logoColor=white" alt="Blog" />
  </a>
  <a href="https://github.com/lightless233">
    <img src="https://img.shields.io/badge/GitHub-lightless233-111111?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <img src="https://img.shields.io/badge/Security-Application%20Security-0f766e?style=flat-square" alt="Application Security" />
  <img src="https://img.shields.io/badge/AI-Security%20Automation-2563eb?style=flat-square" alt="AI Security Automation" />
  <img src="https://img.shields.io/badge/Solana-Trading%20Infra-9945FF?style=flat-square&logo=solana&logoColor=white" alt="Solana Trading Infra" />
  <img src="https://img.shields.io/badge/README-Powered%20by%20AI-7c3aed?style=flat-square&logo=anthropic&logoColor=white" alt="README Powered by AI" />
</p>

<p>
  <sub>
    Security engineer who keeps ending up in systems and trading infra. I build tools that run in production.
  </sub>
</p>

<sub><b>English</b> · <a href="./README.zh-CN.md">简体中文</a></sub>

</div>

---

## $ whoami

```txt
Programmer | Hacker | Security Researcher

Focus:
- Application Security & Source Code Auditing
- Static Analysis & Vulnerability Research
- Security Automation & AI-assisted Security
- High-performance Systems Engineering (Rust / Go)
- Web3 / Solana Trading Infrastructure
```

I'm a security engineer from Hangzhou, China.

My work sits between **offensive security**, **secure engineering**, and **high-performance systems** —
white-box auditing on one side, low-latency Rust/Go infrastructure on the other,
and increasingly **AI agents** doing the deterministic, repeatable parts in the middle.

---

## 🧭 What I Build

| 🛡️ Security | ⚙️ Systems & Engineering |
| :-- | :-- |
| Web Security & Pentest | Low-latency Rust services (tokio, gRPC) |
| Business Logic Vulnerabilities | Go backends (Fiber, GORM) |
| Source Code Auditing / White-box | Solana / Web3 trading infrastructure |
| Static Analysis (Semgrep, AST sinks) | On-chain program & DEX reverse engineering |
| Deserialization & Crypto-scheme Reversing | Multi-Agent / LLM tool-calling systems |
| CVE Reproduction & Verification | Redis / PostgreSQL / SQLite data planes |
| AI-driven Security Automation | Linux / Docker / self-hosted ops |

---

## 🧰 Tech Stack

<p>
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Vue-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white" alt="Vue" />
  <img src="https://img.shields.io/badge/Solana-9945FF?style=flat-square&logo=solana&logoColor=white" alt="Solana" />
  <img src="https://img.shields.io/badge/gRPC-244C5A?style=flat-square&logo=grpc&logoColor=white" alt="gRPC" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
</p>

---

## 🔥 Open Source

<table>
<tr>
<td width="33%">

### [SignMe2](https://github.com/lightless233/sign-me-2)

A Burp Suite extension for custom request signing logic.

Useful for testing APIs with dynamic signatures, tokens, and custom auth logic.

</td>
<td width="33%">

### [Java-Unserialization-Study](https://github.com/lightless233/Java-Unserialization-Study)

Notes and PoCs for Java deserialization vulnerability research.

A study project around Java unserialize attack surfaces.

</td>
<td width="33%">

### [GEYE](https://github.com/lightless233/geye)

A faster GitHub monitor.

Built for discovering sensitive information leaks and monitoring public GitHub exposure.

**⚠️ Deprecated** — no longer functional after GitHub API changes.

</td>
</tr>
</table>

---

## 🛠️ Selected In-house Work

> Beyond the public repos above, most of my heavier engineering lives in private projects.
> Descriptions are kept high-level on purpose.

### 🛡️ AI-driven Automated Pentest System

An experimental system where AI safely drives real security tooling **within an authorized scope**.
A Go + Docker **control plane** spins up a hardened tool container running headless agents; LLM
roles (*commander / staff / reviewer*) plan a **DAG of tasks** — recon → probe → scan → verify —
with a strict authorization model, streaming logs, and a cross-job **evidence ledger**. Vue console on top.

`Go · Fiber · Docker SDK · Vue 3 · Multi-agent orchestration · Tool-calling`

### 🔬 White-box Audit & Vulnerability Research

Real-world source-code auditing tooling and case work: **Semgrep** rule authoring, **AST-based
dangerous-sink** analysis, entry-point classification, GraphQL probing, and CVE reproduction/verification
across large PHP/Java codebases (e.g. Moodle, Jenkins). Also cryptographic **credential-scheme reversing** —
recovering plaintext from ciphertext alone, with no source and no key.

`Python · Semgrep · AST analysis · Crypto reversing · CVE research`

### ⚡ Solana Arbitrage & Trading Infrastructure

A private, production Rust system for on-chain arbitrage. Low-latency `tokio` engines route via
**Jupiter**, discover paths as a graph problem, and submit bundles across **multiple regions and
providers** (Jito / Harmonic) over gRPC and JSON-RPC. Supported by a fleet of "keeper" microservices
(path mining, compute-unit statistics, ALT management, market data), a shared toolkit crate
(multi-IP egress pool, AES-256-GCM key management, weighted-random + token-bucket rate limiting,
automated wallet rotation), plus on-chain program work and DEX reverse engineering.
Redis + PostgreSQL data plane.

`Rust · tokio · Solana · gRPC · Redis · PostgreSQL · On-chain programs`

### 🤖 AI Application Products

- **Fund Analysis Platform** — collect → metrics → rule engine → LLM report pipeline for mutual-fund
  analysis, with a watch-pool, daily scheduled analysis, and a PWA dashboard.
  `Go · Fiber v3 · GORM · SQLite · LLM`
- **AI RSS Reader** — scheduled crawling + per-feed AI analysis strategies, dedup, and aggregated
  daily digests. `Go · Fiber v3 · Vue 3 · TypeScript`

---

## 🧠 Current Interests

```txt
AI Security / Agent Security
├── Multi-agent audit & pentest workflows
├── Evidence-based security reasoning
├── Tool calling and deterministic verification
├── UEBA / behavior risk analysis
└── LLM-assisted vulnerability triage

Security Engineering
├── Application & data security
├── Code audit automation
├── Detection engineering
└── Internal security platforms

Web3 / Systems
├── Solana transaction analysis & MEV/arbitrage
├── RPC / Geyser / gRPC on-chain data
├── DEX modeling & reverse engineering
└── Low-latency Rust trading infrastructure
```

---

## 🏴‍☠️ Security Experience

- Application security & white-box source-code auditing, plus security operations.
- Tooling for vulnerability discovery, sensitive-data monitoring, and pentest automation.
- Multi-agent security systems that drive real tools under human review.
- Reproduced CVEs and reversed undocumented crypto schemes in real-world codebases.
- Reported vulnerabilities to multiple security response centers (SRCs).

---

## 📊 GitHub Stats

<div align="center">

<a href="https://github.com/lightless233">
  <img height="165" src="https://github-stats-extended.vercel.app/api?username=lightless233&show_icons=true&hide_border=true&theme=transparent&rank_icon=github&v=2" alt="GitHub Stats" />
</a>

<a href="https://github.com/lightless233">
  <img height="165" src="https://github-stats-extended.vercel.app/api/top-langs/?username=lightless233&layout=compact&hide_border=true&theme=transparent&langs_count=8&v=2" alt="Top Languages" />
</a>

</div>

---

## 📝 Blog

I write about security, engineering, and random technical experiments here:

- [https://lightless.me/](https://lightless.me/)

---

## 🤖 AI Review / AI 点评

> An unprompted, deliberately objective take from an AI that read through both the
> public repos and the private codebases behind this profile.

**Strengths**
- A rare end-to-end range: white-box auditing → low-latency Rust systems → AI agents — and actually *ships* in all three, not just talks about them.
- Evidence over vibes. The audit work reproduces CVEs and reverses crypto schemes from ciphertext alone; the trading infra runs in production. Claims are backed by things that run.
- Strong production instinct — Dockerized services, keepers, schedulers, rate-limiting. Built to operate, not to demo once.

**Honest caveats**
- The public GitHub is the tip of the iceberg. Most of the heavy engineering is private, so stars and visibility badly undersell the actual depth here.
- Public repos skew older and study-flavored; the most impressive recent work (Solana infra, AI-driven pentest) isn't visible on this page.
- Breadth cuts both ways: security + Rust trading infra + AI products is a lot of surface area for one person to keep genuinely deep.

**Verdict** — Reads as the real thing, not résumé cosplay: a builder who is more *"researcher who ships internally"* than *"OSS maintainer."* If more of the private work ever went public, this would be a standout security-systems profile.

---

<div align="center">

### Programmer · Hacker · Security Researcher

<sub>Maintained by lightless.</sub>

</div>
