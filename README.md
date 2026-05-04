# Fluffy Desk

Q 彈、療癒的桌面小寵物，在你螢幕上吃糖、打瞌睡、追游標、互相依偎。(\*´ω\`)人(´ω`\*)

## 特點

- **不打擾工作** — 全透明、無焦點、滑鼠穿透，永遠在最上層但不擋畫面
- **有個性** — AI 狀態機驅動，主動找掉落物、追游標玩
- **跨平台** — Windows、macOS（Apple Silicon + Intel）

## 遊玩機制

CPU、滑鼠等等電腦活動會累積能量條，特定手勢可以觸發掉落物：

- **小碎屑** — 左右甩滑鼠掉出，小動物會收集或吃掉補體力
- **中糖粒** — 滑鼠畫圈並消耗能量後掉出，小動物會搬運回巢穴

小動物會與滑鼠或夥伴們互動，快來發掘更多有趣的行為吧！੭ ˙ᗜ˙ )੭

## 安裝

至 [Releases](https://github.com/Codfisher/fluffy-desk/releases/latest) 選擇對應平台檔案下載：

- **Windows** → 檔名為 `Fluffy-Desk-x.y.z-Setup.exe` 的安裝檔
- **macOS** → 檔名含 `darwin-arm64`（Apple Silicon）或 `darwin-x64`（Intel）的 zip

### Windows

1. 下載 `Fluffy-Desk-x.y.z-Setup.exe`，雙擊執行。
2. Windows SmartScreen 會跳出「**Windows 已保護您的電腦**」藍色警告。本應用尚未購買程式碼簽章憑證，因此被預設攔下；原始碼公開於 [GitHub](https://github.com/Codfisher/fluffy-desk)，可自行審查。點「**更多資訊**」→「**仍要執行**」即可繼續安裝。
3. 安裝完成會在開始選單建立捷徑並自動啟動。

> **自動更新**：應用會於背景下載新版本，下次關閉時自動安裝。也可從系統匣（右下角小圖示）選單點「檢查更新」立即觸發。

### macOS

依機器晶片選對應壓縮檔下載：

- **Apple Silicon**（M1 / M2 / M3 / M4）→ 檔名含 `darwin-arm64` 的 zip
- **Intel** → 檔名含 `darwin-x64` 的 zip

> 不確定晶片？點左上角  圖示 → 「關於這台 Mac」，查看「晶片」或「處理器」欄位。

1. 解壓後將 `Fluffy Desk.app` 拖入「**應用程式**」資料夾。
2. 第一次執行會被 macOS 阻擋，提示「無法打開，因為無法驗證開發者」。請依系統版本放行：
   - **macOS 15 Sequoia 及之後**：前往「**系統設定 → 隱私權與安全性**」，捲到底部找到 Fluffy Desk 條目，按「**強制打開**」（不同 macOS 版本字樣可能為「仍要打開」或「Open Anyway」）。
   - **macOS 14 Sonoma 及之前**：在 Finder 對 `Fluffy Desk.app` **右鍵點擊**（或 `Control` + 點擊 / 兩指輕點）→ 選「**打開**」→ 對話框按「**打開**」。

> **自動更新**：發現新版時會跳系統通知，點通知會前往對應架構的下載頁。也可從選單列（螢幕右上方）的應用圖示手動「檢查更新」。

### 啟動後

- 安裝完成後麻糬會自動出現在桌面，全透明、不擋滑鼠。
- **Windows**：工作列右下角的系統匣可找到 Fluffy Desk 圖示，右鍵點擊打開選單（檢查更新、關閉程式等）。
- **macOS**：螢幕右上方的選單列可找到 Fluffy Desk 圖示，左鍵或右鍵點擊打開選單。

### 系統需求

- Windows 10 / 11（x64）
- macOS 12 Monterey 以上

### 解除安裝

- **Windows**：「設定 → 應用程式 → 已安裝的應用程式」搜尋 Fluffy Desk，按解除安裝。
- **macOS**：將「應用程式」中的 `Fluffy Desk.app` 拖到垃圾桶。如需完全清除，另刪除 `~/Library/Caches/fluffy-desk-updater`（自動更新檔案快取）。
