# 🐸 Diandengwa · Screen-free AI Learning Engine for K12

> **AI that empowers thinking, not replaces it.**

[![License: AGPL-3.0](https://img.shields.io/badge/License-AGPL--3.0-blue.svg)](./LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](./CONTRIBUTING.md)
[![Star this repo](https://img.shields.io/github/stars/diandengwa/diandengwa?style=social)](https://github.com/diandengwa/diandengwa)

[简体中文](./README_CN.md) · English

---

## 💡 Vision

In an era where AI reshapes the world at the speed of light, we believe: **the best educational technology should let children hear knowledge — not stare at screens.**

Diandengwa is an open-source **Socratic instruction layer** that stops AI from spoon-feeding answers to children. It wraps mainstream LLMs (Doubao, DeepSeek, Qwen, Kimi, ChatGPT, Claude, etc.) with a guided 4-step prompting flow:

**① Accept emotion → ② Diagnose the error → ③ Give an analogy → ④ Ask a follow-up**

No screen required. No direct answers allowed. Designed for Chinese K12 — open for global adaptation.

---

## 🎯 One-Line Comparison

| Without Diandengwa | With Diandengwa |
|-------------------|-----------------|
| **Child**: "How do I solve this?"<br>**AI**: Outputs answer + steps directly | **Child**: "How do I solve this?"<br>**AI**: "Take your time. Tell me, where exactly are you stuck? Can't understand the problem, or is there one step you can't get past?" |

---

## 📦 What's Inside

### 1. 🧠 School-Level Prompt Library `/K12-learning-prompts`

| Level | Focus | Status |
|-------|-------|--------|
| Primary Lower (Grades 1-3) | Interest Protection | ✅ Ready |
| Primary Upper (Grades 4-6) | Learning Skills | ✅ Ready |
| Middle School (Grades 7-9) | Exam Awareness | ✅ Ready |
| High School (Grades 10-12) | Metacognition | ✅ Ready |

### 2. 🔌 Integration Guides `/integrations`

| Integration | Status |
|-------------|--------|
| [Doubao / DeepSeek / Qwen Agent Setup](./integrations/doubao-kimi-agent/) | ✅ Ready |
| [Smart Speaker Guide (Xiaomi/Xiaodu/Tmall)](./integrations/smart-speaker/) | 🔨 Phase 2 |
| Home Printer Bridge | 🔨 Planned |

### 3. 🛠️ MCP Configuration Files

- `SKILL.md` — MCP protocol config
- `skill.json` — Structured definition

---

## 🚀 Quick Start

### Option 1: 3-Minute Setup (Simplest, Recommended)

1. Choose the prompt file matching your child's grade from `K12-learning-prompts/`
2. Copy the prompt content
3. Paste it into any AI assistant's "System Prompt" or "Character Settings"

> 📖 Full guide: [Doubao/DeepSeek/Qwen Integration](./integrations/doubao-kimi-agent/)

### Option 2: MCP Protocol Integration

Use MCP-compatible tools (Cursor, Claude Desktop, etc.), clone this repo, and configure.

---

## 📋 Roadmap

| Feature | Status | ETA |
|---------|--------|-----|
| Doubao/DeepSeek/Qwen Integration | ✅ Done | - |
| Four School-Level Prompts | ✅ Done | - |
| Smart Speaker (Xiaomi MiGPT first) | 🔨 Phase 2 | Q2-Q3 2026 |
| Xiaodu/Tmall Skills Listing | 📋 Planned | Q3-Q4 2026 |
| Home Printer Bridge | 📋 Planned | Q3 2026 |
| More Prompt Variations | 📝 Ongoing | - |

[View on GitHub Projects →](https://github.com/orgs/diandengwa/projects)

---

## 🤝 Contributing

See our [Community Contribution Guide](./CONTRIBUTING.md).

We welcome:
- 💻 **Developers**: Hardware bridges, MCP tools, smart speaker plugins
- 🎓 **Teachers/Parents**: "Soul-follow-up questions" — the one-liners that help kids break through

---

## 📄 License

Diandengwa core engine is **AGPL-3.0** open source.

> Free for individuals and schools; commercial licensing required for SaaS re-wrapping.

- → [View LICENSE](./LICENSE)
- → [Commercial Licensing](./COMMERCIAL.md)
- → [Security Policy](./SECURITY.md)

---

*Diandengwa — helping every child learn to think independently in the AI era.*
