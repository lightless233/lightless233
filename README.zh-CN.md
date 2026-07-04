<div align="center">

# 👋 你好，我是 lightless

### 安全工程师 · Hacker · 系统构建者

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
    做安全出身，却总一头扎进系统和交易基础设施。我写的是真正跑在生产环境里的工具。
  </sub>
</p>

<sub><a href="./README.md">English</a> · <b>简体中文</b></sub>

</div>

---

## $ whoami

```txt
程序员 | Hacker | 安全研究员

方向：
- 应用安全 & 源码审计
- 静态分析 & 漏洞研究
- 安全自动化 & AI 辅助安全
- 高性能系统工程（Rust / Go）
- Web3 / Solana 交易基础设施
```

我是一名来自中国杭州的安全工程师。

我的工作横跨 **攻防安全**、**安全工程** 与 **高性能系统**——
一端是白盒代码审计，另一端是低延迟的 Rust/Go 基础设施，
中间越来越多地交给 **AI Agent** 去处理那些确定性、可重复的部分。

---

## 🧭 我在做什么

| 🛡️ 安全 | ⚙️ 系统 & 工程 |
| :-- | :-- |
| Web 安全 & 渗透测试 | 低延迟 Rust 服务（tokio、gRPC） |
| 业务逻辑漏洞 | Go 后端（Fiber、GORM） |
| 源码审计 / 白盒 | Solana / Web3 交易基础设施 |
| 静态分析（Semgrep、AST sink） | 链上程序 & DEX 逆向 |
| 反序列化 & 加密方案逆向 | 多 Agent / LLM 工具调用系统 |
| CVE 复现与验证 | Redis / PostgreSQL / SQLite 数据层 |
| AI 驱动的安全自动化 | Linux / Docker / 自托管运维 |

---

## 🧰 技术栈

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

## 🔥 开源项目

<table>
<tr>
<td width="50%">

### [GEYE](https://github.com/lightless233/geye)

更快的 GitHub 监控工具。

用于发现敏感信息泄露、监控 GitHub 上的公开暴露面。

</td>
<td width="50%">

### [Java-Unserialization-Study](https://github.com/lightless233/Java-Unserialization-Study)

Java 反序列化漏洞研究的笔记与 PoC。

围绕 Java 反序列化攻击面的学习型项目。

</td>
</tr>

<tr>
<td width="50%">

### [SignMe2](https://github.com/lightless233/sign-me-2)

用于自定义请求签名逻辑的 Burp Suite 插件。

适合测试带动态签名、Token、自定义鉴权逻辑的 API。

</td>
<td width="50%">

### CVE-2020-25396

已上报并获得署名的漏洞贡献。

持续向多个安全应急响应中心（SRC）负责任披露工作的一部分。

</td>
</tr>
</table>

---

## 🛠️ 部分非公开项目

> 除了上面的公开仓库，我更重的工程大多在非公开项目里。
> 这里的描述是刻意保持在高层次的。

### 🛡️ AI 驱动的自动化渗透系统

一个让 AI 在 **授权范围内** 安全地驱动真实安全工具的实验性系统。
Go + Docker 的 **控制平面** 拉起加固过的工具容器、运行无头 Agent；LLM 以
*指挥官 / 参谋 / 验收官* 等角色编排一张 **任务 DAG**——侦察 → 探活 → 扫描 → 验证——
带有严格的授权模型、流式日志，以及跨任务的 **产出账本**。上层是 Vue 控制台。

`Go · Fiber · Docker SDK · Vue 3 · 多 Agent 编排 · 工具调用`

### 🔬 白盒审计 & 漏洞研究

真实的源码审计工具与案例：**Semgrep** 规则编写、基于 **AST 的危险 sink** 分析、
入口点分类、GraphQL 探测，以及在大型 PHP/Java 代码库（如 Moodle、Jenkins）上的
CVE 复现与验证。还包括加密 **凭证方案逆向**——在没有源码、没有密钥的情况下，仅凭密文还原明文。

`Python · Semgrep · AST 分析 · 加密逆向 · CVE 研究`

### ⚡ Solana 套利 & 交易基础设施

一套非公开的、跑在生产环境的 Rust 链上套利系统。低延迟的 `tokio` 引擎经 **Jupiter** 路由，
把路径发现当作图问题来解，并跨 **多区域、多服务商**（Jito / Harmonic）通过 gRPC 与 JSON-RPC 发送 bundle。
背后由一组 “keeper” 微服务支撑（路径挖掘、计算单元统计、ALT 管理、行情数据），
以及一个共享工具库 crate（多 IP 出口池、AES-256-GCM 密钥管理、加权随机 + 令牌桶限流、自动钱包轮换），
另有链上程序开发与 DEX 逆向。数据面是 Redis + PostgreSQL。

`Rust · tokio · Solana · gRPC · Redis · PostgreSQL · 链上程序`

### 🤖 AI 应用产品

- **基金分析平台** —— 采集 → 指标 → 规则引擎 → LLM 报告 的一整条公募基金分析链路，
  含观察池、每日定时分析与 PWA 看板。
  `Go · Fiber v3 · GORM · SQLite · LLM`
- **AI RSS 阅读器** —— 定时抓取 + 按订阅源分策略的 AI 分析、去重，以及聚合后的每日摘要。
  `Go · Fiber v3 · Vue 3 · TypeScript`

---

## 🧠 当前关注

```txt
AI 安全 / Agent 安全
├── 多 Agent 审计与渗透工作流
├── 基于证据的安全推理
├── 工具调用与确定性验证
├── UEBA / 行为风险分析
└── LLM 辅助的漏洞研判

安全工程
├── 应用安全 & 数据安全
├── 代码审计自动化
├── 检测工程
└── 内部安全平台

Web3 / 系统
├── Solana 交易分析 & MEV/套利
├── RPC / Geyser / gRPC 链上数据
├── DEX 建模与逆向
└── 低延迟 Rust 交易基础设施
```

---

## 🏴‍☠️ 安全经历

- 应用安全 & 白盒源码审计，兼做安全运营。
- 面向漏洞发现、敏感数据监控、渗透流程自动化的工具建设。
- 在人工复核下驱动真实工具的多 Agent 安全系统。
- 在真实代码库中复现 CVE、逆向未公开的加密方案。
- 向多个 SRC 上报漏洞；CVE 贡献者（CVE-2020-25396）。

---

## 📊 GitHub 数据

<div align="center">

<a href="https://github.com/lightless233">
  <img height="165" src="https://github-stats-extended.vercel.app/api?username=lightless233&show_icons=true&hide_border=true&theme=transparent&rank_icon=github&v=2" alt="GitHub Stats" />
</a>

<a href="https://github.com/lightless233">
  <img height="165" src="https://github-stats-extended.vercel.app/api/top-langs/?username=lightless233&layout=compact&hide_border=true&theme=transparent&langs_count=8&v=2" alt="Top Languages" />
</a>

</div>

---

## 📝 博客

我在这里写安全、工程和各种技术随笔：

- [https://lightless.me/](https://lightless.me/)

---

## 🤖 AI 点评 / AI Review

> 一段未经授意、刻意保持客观的评价——来自一个读过这个主页背后
> 公开仓库与非公开代码库的 AI。

**优点**
- 罕见的端到端跨度：白盒审计 → 低延迟 Rust 系统 → AI Agent——而且三块都真能 *落地交付*，不是只停留在嘴上。
- 用证据说话，而非靠感觉。审计工作能复现 CVE、仅凭密文逆向加密方案；交易基础设施跑在生产环境。结论背后都有能跑起来的东西撑着。
- 很强的生产化本能——Docker 化的服务、keeper、调度器、限流。是奔着长期运行去的，不是 demo 一次就完事。

**诚实的短板**
- 公开的 GitHub 只是冰山一角。大部分重工程都在非公开项目里，所以 star 和曝光度严重低估了真实深度。
- 公开仓库偏早期、偏学习性质；最能打的近期工作（Solana 基础设施、AI 驱动渗透）在这个页面上是看不到的。
- 广度是把双刃剑：安全 + Rust 交易基础设施 + AI 产品，对一个人来说是相当大的面，要每块都真正做深并不容易。

**结论** —— 像真东西，不像简历表演：更接近 *“对内交付的研究者”*，而非 *“开源维护者”*。如果更多非公开的工作能开源出来，这会是一个很能打的安全 + 系统方向主页。

---

<div align="center">

### 程序员 · Hacker · 安全研究员

<sub>由 lightless 维护。</sub>

</div>
