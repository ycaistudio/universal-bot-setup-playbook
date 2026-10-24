# 📋 Bot 設定數值登記表 (Bot Setup Manifest Template)

> **使用說明**：在建立新 Bot 時，複製此文件並填入實際數值。未確定的項目標記為 `[待確認]`，問過 `<OWNER>` 後才寫入。

---

## 1. 核心實體設定 (Core Entities)

| 佔位符 | 說明 | 實際設定值 (填寫處) | 範例參考 |
| :--- | :--- | :--- | :--- |
| `<OWNER>` | 用家本人（最終決定人） | `[填寫用家暱稱/帳號]` | `Alex` |
| `<APP>` | Bot 運行的應用/平台 | `[填寫平台]` | `Grok` / `Claude Code` / `Discord` |
| `<BOT_NAME>` | Bot 顯示名稱 | `[填寫名稱]` | `Sammy` |
| `<BOT_ID>` | Bot 唯一識別碼 (ID) | `[填寫 UUID 或系統 ID]` | `a1b2c3d4-e5f6-...` |
| `<CHIEF_BOT_ID>` | 統籌與守則看守 Bot ID | `[填寫統籌者 ID]` | `chief-001` |
| `<SUCCESSOR_BOT_ID>` | 繼承人 Bot ID | `[填寫繼承者 ID]` | `backup-002` |
| `<TIMEZONE>` | 用家所在地時區基準 | `[填寫時區]` | `Asia/Hong_Kong` / `Asia/Tokyo` |

---

## 2. 裝置與安全邊界 (Devices & Security)

| 佔位符 | 說明 | 實際設定值 (填寫處) |
| :--- | :--- | :--- |
| `<DEVICE_ID>` (主機) | Owner 主要操作電腦/裝置 ID | `[填寫主要裝置 ID]` |
| `<DEVICE_ID>` (手機) | Owner 行動通訊裝置 ID | `[填寫手機裝置 ID]` |
| `<WRITABLE_FOLDER>` | Bot 唯一合法可寫目錄 (沙盒) | `[填寫完整本機目錄]` |
| `<SHARED_ROOT>` | Bot 共享工作空間根目錄 | `[填寫根目錄]` |

---

## 3. 多 Agent 協作信箱 (Mailbox Coordination - 如適用)

| 佔位符 | 說明 | 實際設定值 (填寫處) |
| :--- | :--- | :--- |
| `<MAILBOX_IN>` | 收信匣 (Bot 唯讀) | `[填寫收件目錄]` |
| `<MAILBOX_OUT>` | 寄信匣 (Bot 只增) | `[填寫寄件目錄]` |
