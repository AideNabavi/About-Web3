<div align="center">

# 🛡️ Web3 Bug Bounty Hunting AI Skills

### Train Claude Code and other AI assistants to hunt smart contract vulnerabilities like an experienced Web3 security researcher.

Built from **2,749 Immunefi reports**, **681 reproduced DeFi hacks**, professional audit methodologies, and real-world bug bounty experience.

<p>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)
![Skills](https://img.shields.io/badge/AI%20Skills-11-blue)
![Immunefi Reports](https://img.shields.io/badge/Immunefi-2%2C749%20Reports-orange)
![DeFi Hacks](https://img.shields.io/badge/DeFiHackLabs-681%20Reproductions-red)
![Solidity](https://img.shields.io/badge/Solidity-Security-success)
![AI Ready](https://img.shields.io/badge/AI-Claude%20%7C%20Cursor%20%7C%20GPT-purple)

</p>

**Stop teaching your AI from scratch.
Give it an entire Web3 security knowledge base instead.**

</div>

---

# 🚀 Why This Repository?

Smart contract bug bounty hunting is often repetitive.

Researchers repeatedly:

* 📖 Read hundreds of Solidity files manually
* 🔍 Search for the same vulnerability patterns
* 🧠 Remember exploit techniques from memory
* 🛠️ Rewrite Foundry PoCs every engagement
* 📝 Write bug reports from scratch
* 🔄 Repeat the same workflow for every target

This repository transforms that manual workflow into reusable **AI Skills**.

Instead of explaining everything every time, simply let your AI read these files once and it gains a structured methodology for:

* 🎯 Target prioritization
* 🔬 Vulnerability discovery
* 🔎 Pattern recognition
* ⚡ Grep automation
* 🧪 Proof-of-Concept generation
* 📄 Professional report writing
* 📚 Learning from real-world exploits

---

# 🤖 Compatible AI Tools

Works with any AI capable of reading project files.

✅ Claude Code

✅ Claude.ai

✅ Cursor

✅ GPT-based coding assistants

✅ VSCode AI extensions

✅ Any local LLM

---

# 📂 Repository Structure

| File                                       | Description                                                                         |
| ------------------------------------------ | ----------------------------------------------------------------------------------- |
| **00-START-HERE.md**                       | 📖 Repository roadmap and navigation                                                |
| **01-foundation.md**                       | 🧠 Hunter mindset, reconnaissance, target scoring methodology                       |
| **02-bug-classes.md**                      | 🚨 10 major vulnerability classes with Solidity examples and real Immunefi findings |
| **03-grep-arsenal.md**                     | 🔍 Grep and Regex patterns for rapidly locating vulnerabilities                     |
| **04-poc-and-foundry.md**                  | 🛠️ 18 reusable Foundry Proof-of-Concept templates                                  |
| **05-triage-report-examples.md**           | 📄 Validation checklist, report format, and paid report examples                    |
| **06-methodology-research.md**             | 📚 Audit methodologies from leading security firms                                  |
| **07-case-study-role-misconfiguration.md** | 🔬 Complete real-world bug hunting walkthrough                                      |
| **08-ai-tools.md**                         | 🤖 AI agents, automation tools, and recommended workflows                           |
| **09-live-hunt-zksync.md**                 | 🛡️ Hardened Layer-2 bridge attack surface analysis                                 |
| **36-solidity-audit-mcp.md**               | ⚙️ Claude Code MCP integration with Slither, Aderyn, and SWC                        |

---

# 🎯 The 10 Core Bug Classes

```
01  Accounting Desynchronization
02  Access Control
03  Incomplete Execution Paths
04  Off-by-One Errors
05  Oracle Price Manipulation
06  ERC4626 Vault Attacks
07  Reentrancy
08  Flash Loan Attacks
09  Signature Replay
10  Proxy & Upgrade Vulnerabilities
```

Each section contains:

* ✅ How the vulnerability works
* ✅ Real Solidity examples
* ✅ Real Immunefi reports
* ✅ Attack methodology
* ✅ Detection strategy
* ✅ Manual review checklist
* ✅ AI prompts
* ✅ Common false positives

---

# 💡 Golden Rule

> **Always inspect sibling functions.**

If one function contains:

* `onlyOwner`
* `onlyRole`
* `nonReentrant`
* `whenNotPaused`

...verify every function performing similar logic.

Many critical vulnerabilities arise because **one sibling function lacks the required protection**.

This simple habit explains a surprisingly large portion of high-impact findings.

---

# ⚡ Getting Started

## Option 1 — Add as a Claude Skill

```bash
git clone https://github.com/shuvonsec/web3-bug-bounty-hunting-ai-skills.git .claude/skills/web3
claude
```

Inside Claude Code:

```text
Read all files in .claude/skills/web3 starting from 00-START-HERE.md
```

---

## Option 2 — Standalone Workspace

```bash
git clone https://github.com/shuvonsec/web3-bug-bounty-hunting-ai-skills.git

cd web3-bug-bounty-hunting-ai-skills

claude
```

---

## Option 3 — Quick Start

If you only have 30 minutes:

```text
Read:

02-bug-classes.md

04-poc-and-foundry.md
```

These two files provide the majority of the practical value.

---

# 📊 Project Statistics

| Metric                        |      Value |
| ----------------------------- | ---------: |
| 📑 Immunefi Reports           |  **2,749** |
| 🔴 Critical Findings          |    **406** |
| 🟠 High Findings              |    **616** |
| 💰 Total Public Rewards       | **$100M+** |
| 🔥 DeFiHackLabs Reproductions |    **681** |
| 🛡️ Nethermind Audit Reports  |    **166** |
| 🌐 Protocols Covered          |     **51** |
| 📚 AI Skill Files             |     **11** |

---

# 🎓 What You'll Learn

After working through these skill files, your AI assistant can help you:

* 🔍 Review Solidity codebases
* 🧠 Recognize common exploit patterns
* 🧪 Generate Foundry PoCs
* 📄 Draft professional bug bounty reports
* ⚡ Prioritize promising targets
* 🛡️ Understand modern audit methodologies
* 📚 Learn from historical exploits

---

# 🔗 Related Projects

| Repository                | Description                                                                     |
| ------------------------- | ------------------------------------------------------------------------------- |
| **claude-bug-bounty**     | Automatically maps attack surfaces and generates structured bug bounty reports. |
| **public-skills-builder** | Convert hundreds of public writeups into reusable AI skill files.               |

---

# ⭐ Contributing

Contributions are welcome!

If you'd like to improve vulnerability coverage, update case studies, add new exploit techniques, or enhance AI workflows, feel free to open an issue or submit a pull request.

---

# 📜 License

Released under the **MIT License**.

Use it, modify it, fork it, and build better AI-powered security tooling.

If this repository helps your research, consider giving it a ⭐ on GitHub.
