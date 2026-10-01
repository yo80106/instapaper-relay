# instapaper-relay

Instapaper 模組的中繼站 repo：暫存要 relay 到 Instapaper 的 markdown 檔案，讓 Instapaper 的 Simple API 能抓到內容。

每篇筆記上傳超過 1 小時就會被 `.github/workflows/cleanup.yml` 刪除（每小時檢查一次，實際存活約 1～2 小時）。刪除後 Action 會重建 git 歷史，分支上不留已刪筆記的 commit。設計脈絡見 vault 裡的 Instapaper模組 專案筆記。
