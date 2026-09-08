# Ayuan DPS Lite Updates

這個 Repository 是 **阿源 DPS Lite 朋友版** 的自動更新來源。

- `latest.json`：固定更新 Feed
- `releases/`：自動更新 ZIP
- 更新包由 Ayuan DPS Lite 透過 HTTPS 下載並進行 SHA256 驗證
- 程式會在戰鬥結束後才套用更新，並保留 `data/` 下的設定、LOG 與使用者資料

> 注意：要讓朋友端不登入 GitHub 也能自動更新，此 Repository 必須設為 **Public**。
