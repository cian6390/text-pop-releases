# Passin Releases

這裡存放 **[Passin](https://github.com/cian6390/passin)** 桌面應用程式的正式發布安裝檔與自動更新產物。

Passin 是一款 Mac 上的貼上管理工具，幫助你隨時保存並快速貼上文字片段（Snippets）、表情符號（Emoji）以及迷因圖（Memes）。

---

## 下載與安裝 (Download & Install)

請前往 **[Releases 頁面](https://github.com/cian6390/passin-releases/releases/latest)** 下載最新版本：

- **macOS (Apple Silicon, M 系列晶片)**：下載 `Passin_X.Y.Z_aarch64.dmg`。
  - 開啟 DMG 檔案後，將 `Passin.app` 拖曳至 `Applications`（應用程式）資料夾即可完成安裝。

> [!NOTE]
> **系統權限需求**：
> Passin 在背景常駐運行，並透過原生模擬貼上功能將內容直接輸入至焦點視窗。首次執行時，系統會要求授予 **「輔助使用 (Accessibility)」** 權限：
> - 前往「系統設定」➔「隱私權與安全性」➔「輔助使用」
> - 確認已開啟 **Passin** 的權限

---

## 自動更新 (Auto Update)

Passin 內建自動更新機制：
- 每次啟動或點擊設定面板時，程式會自動比對本儲存庫發布的 `latest.json`。
- 更新檔具備 Minisign 數位簽章驗證與 Apple 公證（Notarization），確保安全無虞。

---

## 相關連結

- **專案原始碼**：[cian6390/passin](https://github.com/cian6390/passin)
- **問題回報**：[Issues](https://github.com/cian6390/passin/issues)
