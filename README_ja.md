# coding-voice-assistant

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,30&height=200&section=header&text=coding-voice-assistant&fontSize=36&fontColor=fff&animation=fadeIn&desc=音声で導く%20フルサイクル%20コーディングアシスタント%20(Plugin版)&descSize=18&descAlignY=70" width="100%"/>

<img src="https://raw.githubusercontent.com/kubouchiyuya/kubouchiyuya/main/avatar.jpg" width="120" style="border-radius:50%; margin-top:16px"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=3000&pause=1000&color=F97316&center=true&vCenter=true&multiline=true&width=900&height=140&lines=プラグイン方式+%F0%9F%94%8C;MCP+不要;音声%2B+AI+コーディング)](https://github.com/DenverCoder1/readme-typing-svg)

[![GitHub](https://img.shields.io/badge/GitHub-kubouchiyuya-181717?style=for-the-badge&logo=github)](https://github.com/kubouchiyuya)
[![LP](https://img.shields.io/badge/Consulting%20LP-F97316?style=for-the-badge&logo=vercel&logoColor=white)](https://consulting-payment-tool.vercel.app)

</div>

---

## このツールでできること

このリポジトリは、音声付きコーディングアシスタントのプラグイン版です。Claude Code に直接つなぐので、別の MCP サーバーを立てずに音声通知を使えます。

セットアップを軽くしつつ、必要なときだけ声で進行を知らせることを目的にしています。

---

## ✨ 機能

| 機能 | 説明 |
|---|---|
| プラグイン構成 | Claude Code Hooks を利用した連携 |
| MCP 不要 | 運用の手数が少ない |
| 音声ガイド | 音声で進行や完了を通知 |
| 非エンジニア向け | 平易な導入説明 |
| ローカル優先 | 手元の音声環境で運用可能 |

---

## 🚀 はじめかた

```bash
cd ~/Projects
git clone https://github.com/kubouchiyuya/coding-voice-assistant.git
cd coding-voice-assistant
./scripts/settings.sh
```

---

## 🏗️ アーキテクチャ

```mermaid
graph TD
    Plugin[Claude Code プラグイン] --> Hooks[Hooks]
    Hooks --> Notify[scripts/notify.sh]
    Notify --> Voice[音声エンジン]
    Voice --> Agents[アシスタントエージェント]
    Agents --> Plugin
```

---

## 🛠️ 技術スタック

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![VOICEVOX](https://img.shields.io/badge/VOICEVOX-Free-brightgreen?style=for-the-badge)
![Claude%20Code](https://img.shields.io/badge/Claude%20Code-Plugin-F97316?style=for-the-badge)

---

## 👤 作者

<div align="center">

| | |
|---|---|
| **窪内裕也（MASA2 / MASA サブ）** | 美容室オーナー → AI アーキテクト |
| 拠点 | 大阪 |
| 所属 | AKATSUKI / Miyabi Society |
| アイデンティティ | AI × 美容業界 × 非エンジニア |

</div>
