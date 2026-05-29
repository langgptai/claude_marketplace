<div align="center">

# 🧩 LangGPT Claude Code 技能市场

**云中江树出品 · 提示词与 Agent 核心技能合集**

人人都能写出高质量提示词，人人都能用上专业级 Agent 技能。

[![LangGPT](https://img.shields.io/badge/LangGPT-structured%20prompt-blue.svg)](https://github.com/langgptai/LangGPT)
[![Skills](https://img.shields.io/badge/skills-3-success.svg)]()
[![Author](https://img.shields.io/badge/author-云中江树-orange.svg)]()

</div>

---

## 📖 这是什么

这是 [LangGPT](https://github.com/langgptai/LangGPT) 官方维护的 **Claude Code 技能市场（Plugin Marketplace）**，汇集云中江树（yzfly）打磨的提示词与 Agent 核心技能。一行命令即可安装，安装后技能会自动更新到对应仓库的最新版本。

## 🚀 快速开始

### 1. 添加市场

```bash
/plugin marketplace add langgptai/claude_marketplace
```

### 2. 安装技能

```bash
/plugin install structured-prompt-writer@langgpt   # 结构化提示词写作
/plugin install cto@langgpt                         # CTO：把 idea 想清楚
/plugin install mind-clone@langgpt                  # 心智克隆
```

### 3. 管理

```bash
/plugin marketplace update langgpt   # 更新市场索引
/plugin list                         # 查看已安装技能
```

## 🎁 技能一览

| 技能 | 安装名 | 说明 | 源仓库 |
|------|--------|------|--------|
| 📝 **结构化提示词写作器** | `structured-prompt-writer` | LangGPT 结构化提示词写作技能，内置 395+ 提示词模板，支持详细 / 简单两种模式，用于创建专业的 AI 角色、系统、任务提示词。 | [structured-prompt-skill](https://github.com/yzfly/structured-prompt-skill) |
| 🏗️ **CTO** | `cto` | 既能做顶层架构、又能下场写代码的创业 CTO。一场对话把模糊想法变成可落地的软件设计，也能在现有代码库里调研、重构、写功能、调试、交付 PR。 | [CTO-Skills](https://github.com/yzfly/CTO-Skills) |
| 🧠 **心智克隆** | `mind-clone` | 认知数字孪生：把一个人的认知操作系统加载进 AI，模拟其决策、偏见与内在冲突。支持自定义对象，也内置名人 / 专家人格。 | [Mind-Cloning-Engineering](https://github.com/yzfly/Mind-Cloning-Engineering) |

> 各技能托管在独立仓库中，本市场以 `github` 源引用，**不复制代码**——源仓库更新后，执行 `/plugin marketplace update langgpt` 即可获取最新版本。

## 🤝 关于

- **作者**：云中江树
- **微信公众号**：云中江树
- **LangGPT 框架**：<https://github.com/langgptai/LangGPT>
- **理念**：结构化提示词（Structured Prompt）+ 元提示词（Meta-Prompt），最流行的提示词落地范式。

欢迎提交优质技能、反馈问题，一起把这个市场建设得更好。

---

<div align="center">
Made with ❤️ by 云中江树 · LangGPT
</div>
