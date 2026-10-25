# OLAPI Connect

Windows 桌面客戶端，一鍵把 OLAPI 中轉接入本機的 AI 工具。免手動改設定檔、免複製金鑰。

## 支援的客戶端

| 客戶端 | 寫入位置 | 協議 |
|---|---|---|
| Codex | `~/.codex/config.toml` + `auth.json` | OpenAI Responses |
| Claude Code | `~/.claude/settings.json` | Anthropic Messages |
| Gemini CLI | `~/.gemini/.env` + `settings.json` | Gemini 原生 `v1beta` |
| OpenCode | `~/.config/opencode/opencode.jsonc` | OpenAI 相容 |

設定頁就是首頁。登入後選擇分組與模型，按「一鍵配置」即可；既有設定會先備份再合併寫入，不會覆蓋你其他的供應商。

## 下載

到 [Releases](https://github.com/dirty1234dirty-dev/OLAPIConnect/releases/latest) 下載 `OLAPIConnect.exe`（單檔，免安裝、免 Python）。

## 說明

- 金鑰只存在於你的電腦與 OLAPI 伺服器之間，客戶端不轉存到任何第三方。
- 每次開啟都會自動拉取最新的模型清單，只顯示你的金鑰實際能呼叫的模型。
- 錯誤訊息不會顯示上游供應商名稱。
