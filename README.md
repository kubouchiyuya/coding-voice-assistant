# coding-voice-assistant

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,30&height=200&section=header&text=coding-voice-assistant&fontSize=36&fontColor=fff&animation=fadeIn&desc=Voice-Guided%20Full-Cycle%20Coding%20Assistant%20(Plugin%20Edition)&descSize=18&descAlignY=70" width="100%"/>

<img src="https://raw.githubusercontent.com/kubouchiyuya/kubouchiyuya/main/avatar.jpg" width="120" style="border-radius:50%; margin-top:16px"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=3000&pause=1000&color=F97316&center=true&vCenter=true&multiline=true&width=900&height=140&lines=Plugin-Based+%F0%9F%94%8C;No+MCP+Required;Voice+%2B+AI+Coding)](https://github.com/DenverCoder1/readme-typing-svg)

[![GitHub](https://img.shields.io/badge/GitHub-kubouchiyuya-181717?style=for-the-badge&logo=github)](https://github.com/kubouchiyuya)
[![LP](https://img.shields.io/badge/Consulting%20LP-F97316?style=for-the-badge&logo=vercel&logoColor=white)](https://consulting-payment-tool.vercel.app)

</div>

---

## What This Does

This is the plugin edition of the voice-guided coding assistant. It gives Claude Code voice-aware feedback without requiring a separate MCP server.

The design goal is simple: keep the workflow light, reduce setup friction, and still let the assistant speak when it matters.

---

## ✨ Features

| Feature | Description |
|---|---|
| Plugin workflow | Hooks-based integration with Claude Code |
| No MCP required | Smaller operational footprint |
| Voice guidance | Spoken prompts and updates |
| Non-engineer friendly | Clear setup steps and plain-language explanations |
| Local-first | Can run with local voice tooling |

---

## 🚀 Quick Start

```bash
cd ~/Projects
git clone https://github.com/kubouchiyuya/coding-voice-assistant.git
cd coding-voice-assistant
./scripts/settings.sh
```

---

## 🏗️ Architecture

```mermaid
graph TD
    Plugin[Claude Code Plugin] --> Hooks[Hooks]
    Hooks --> Notify[scripts/notify.sh]
    Notify --> Voice[Voice Engine]
    Voice --> Agents[Assistant Agents]
    Agents --> Plugin
```

---

## 🛠️ Tech Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![VOICEVOX](https://img.shields.io/badge/VOICEVOX-Free-brightgreen?style=for-the-badge)
![Claude%20Code](https://img.shields.io/badge/Claude%20Code-Plugin-F97316?style=for-the-badge)

---

## 👤 Author

<div align="center">

| | |
|---|---|
| **Yuya Kubouchi (MASA2 / MASA Sub)** | Beauty Salon Owner → AI Architect |
| Location | Osaka, Japan |
| System | AKATSUKI / Miyabi Society |
| Identity | AI × Beauty Industry × Non-Engineer |

</div>
