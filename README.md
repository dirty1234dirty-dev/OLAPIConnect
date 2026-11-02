# OlithmRouter Connect（原 OLAPI Connect）

[![官網](https://img.shields.io/badge/官網-api.olithm.eu.cc-0a84ff?style=for-the-badge)](https://api.olithm.eu.cc)
[![下載](https://img.shields.io/badge/下載-Releases-2ea043?style=for-the-badge&logo=github)](https://github.com/dirty1234dirty-dev/OLAPIConnect/releases/latest)
![平台](https://img.shields.io/badge/平台-Windows-blue?style=flat-square&logo=windows)
![免費](https://img.shields.io/badge/客戶端-永久免費-10b981?style=flat-square)

Windows 桌面客戶端，**一鍵**把 [OlithmRouter](https://api.olithm.eu.cc) 便宜 AI 中轉站接入本機的 AI 工具：免手動改設定檔、免複製金鑰、免翻牆設定。

> 💰 **廉價** — 低至官方價 1 折起（cheap API / 便宜API），快取命中只收快取價
> 🛡️ **穩定** — 穩定分組可用率 99%+，上游真出錯才自動切換
> 🧰 **多功能** — OpenAI / Anthropic / Gemini 三協議一個入口
> 🌏 **全球線路優化** — Cloudflare 全球節點，國內直連、台灣香港海外皆快

## 支援的客戶端 / Supported Clients

| 客戶端 | 寫入位置 | 協議 |
|---|---|---|
| Codex | `~/.codex/config.toml` + `auth.json` | OpenAI Responses |
| Claude Code | `~/.claude/settings.json` | Anthropic Messages |
| Gemini CLI | `~/.gemini/.env` + `settings.json` | Gemini 原生 `v1beta` |
| OpenCode | `~/.config/opencode/opencode.jsonc` | OpenAI 相容 |

設定頁就是首頁。登入後選擇分組與模型，按「一鍵配置」即可；既有設定會先備份再合併寫入，不會覆蓋你其他的供應商。

## 快速開始 / Quick Start

1. 到 [olithm.eu.cc](https://olithm.eu.cc) 註冊並儲值（支持多種支付，低至官方價 1 折起）
2. 到 [模型廣場](https://api.olithm.eu.cc/models) 選分組與模型（GPT / Claude / Gemini / DeepSeek / GLM / Kimi 等）
3. 下載本工具 → 輸入卡號或登入 → 按「**一鍵配置**」
4. 打開 Codex / Claude Code 直接開始用，**按量計費、透明可查**

## 下載 / Download

[Releases](https://github.com/dirty1234dirty-dev/OLAPIConnect/releases/latest) 下載 `OLAPIConnect.exe`（單檔、免安裝、免 Python）。

## English

**OlithmRouter Connect** — official Windows client for the [OlithmRouter AI gateway](https://api.olithm.eu.cc): a cheap LLM API relay (from 10% of official price) that is OpenAI / Anthropic / Gemini compatible. One-click setup for Codex, Claude Code, Gemini CLI and OpenCode. 99%+ uptime on stable groups, automatic failover, prompt caching, itemised billing.

## 說明 / Notes

- 金鑰只存在於你的電腦與 OlithmRouter 伺服器，不經第三方
- 遇到問題？[客服](https://olithm.eu.cc/support)（72 小時內回覆）
- QQ 3021143916 · 微信 wxid_008nf87dt6qt22 · Discord rtu70#7073 · LINE zhangkai97
