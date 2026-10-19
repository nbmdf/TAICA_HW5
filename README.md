# Neon Snake 霓虹貪食蛇

純 HTML、CSS、JavaScript 製作的單檔貪食蛇。遊戲所需程式全部位於 `index.html`，不需套件、CDN、後端或建置流程；本說明文件不影響遊戲執行。

## 本機開啟

以 VS Code 開啟資料夾，編輯 `index.html` 並儲存，再用瀏覽器開啟檔案。修改後重新整理頁面即可。

## 遊戲方式

- 棋盤：20 × 20。方向鍵、WASD 或畫面方向按鈕控制，不可直接反向。
- 吃食物加 10 分並成長；撞牆或身體結束。
- 初速 160 毫秒／格，每顆食物加快 5 毫秒，最快 70 毫秒／格。
- 開始、暫停／繼續、重玩；切換分頁會自動暫停。
- 最高分存於瀏覽器 localStorage，不跨裝置同步。清除網站資料會移除紀錄，儲存不可用時會顯示提示。
- 本機檔案與 GitHub Pages 屬不同來源，最高分不會自動移轉。請在正式網址重新測試儲存。

## GitHub Pages 上線

1. 在 GitHub 建立公開儲存庫，例如 `neon-snake`。
2. 選擇 Add file → Upload files，把 `index.html` 放在儲存庫根目錄並提交。README.md 可選擇一併上傳。
3. 開啟 Settings → Pages。
4. Build and deployment 的 Source 選擇 Deploy from a branch。
5. Branch 選擇存放檔案的分支（通常為 main），資料夾選 /(root)，按 Save。
6. 等待部署完成，從 Pages 設定頁開啟網站連結。一般專案網址格式為 https://帳號.github.io/儲存庫名稱/ 。
7. 後續更新只需重新上傳並提交 index.html，等待部署完成後重新整理網站。

