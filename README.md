# 🐸 点灯蛙 (Diandengwa) K12 无屏 AI 学伴引擎

> **AI 赋智于声，思考还给孩子。**
> *Diandengwa — Screen-free AI learning companion for K12.*

![License: AGPL-3.0](https://img.shields.io/badge/License-AGPL--3.0-blue.svg)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)
[![星标仓库](https://img.shields.io/github/stars/shaowan168/diandengwa?style=social)](https://github.com/shaowan168/diandengwa)

---

## 💡 愿景

在 AI 以光速重塑世界的时代，我们相信：**最好的教育技术，应当让孩子听见知识，而不是盯着屏幕。**

点灯蛙 (Diandengwa) 是一套**防止 AI 直接给答案的开源指令干预层**。它把主流大模型（豆包、Kimi 等）接入苏格拉底式启发引导法——接纳情绪 → 诊断错因 → 给出具象比喻 → 发出追问，让孩子在没有屏幕干扰的环境中，真正学会独立思考。

---

## ⚠️ 开源版 vs 云端服务

| 版本 | 数据来源 | 更新频率 | 适用场景 |
|------|----------|----------|----------|
| **🌐 开源版（本仓库）** | 本地静态提示词 | 仅随仓库更新 | 自行部署、尝鲜体验 |
| **☁️ 云端服务** | 实时同步学校动态考纲 | 每周自动更新 | 深度使用、效果最佳 |

**开源版特点**：
- ✅ 完全免费，代码透明
- ✅ 可本地部署，不依赖网络
- ⚠️ 考纲内容为通用版本，无法匹配孩子学校的实时进度

→ [了解更多云端服务](./COMMERCIAL.md)

---

## 📦 仓库内容

### 1. 🧠 按学段提示词库 `/K12-learning-prompts`

| 学段 | 定位 |
|------|------|
| 小学低年级（1-3年级） | 兴趣保护版 |
| 小学高年级（4-6年级） | 会学能力版 |
| 初中（7-9年级） | 中考意识版 |
| 高中（10-12年级） | 元认知版 |

### 2. 🔌 集成指南 `/integrations`

- [将豆包/Kimi转换为点灯蛙专属智能体](./integrations/doubao-kimi-agent/)
- 智能音箱接入指南 (*敬请期待*)
- 家用打印机桥接方案 (*敬请期待*)

### 3. 🛠️ MCP 配置文件

- `SKILL.md` — MCP 协议配置
- `skill.json` — 结构化定义

---

## 🚀 快速开始

### 方法一：30秒配置（最简单）

复制 `integrations/doubao-kimi-agent/README.md` 中的提示词，粘贴到任意 AI 助手的"角色设定"中。

### 方法二：MCP 协议接入

使用支持 MCP 的工具（Cursor、Claude Desktop 等），克隆本仓库并配置读取即可。

---

## 🤝 参与共建

详细玩法请看 [点灯蛙社区共建指南](./CONTRIBUTING.md)。

我们欢迎：
- 💻 **开发者**：贡献硬件桥接、MCP 工具
- 🎓 **教师/家长**：贡献"灵魂追问"——那些帮助孩子突破难题的一句话

---

## 📄 许可证

点灯蛙核心引擎采用 **AGPL-3.0** 开源协议。

→ [查看 LICENSE](./LICENSE)
→ [商业合作说明](./COMMERCIAL.md)

---

*点灯蛙——让每一个孩子都能在 AI 时代学会独立思考。*
