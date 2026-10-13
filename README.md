# 城市行聊・走讀城鄉

社團法人臺灣城市行聊走讀城鄉學會官方網站（純靜態網頁）。

- `index.html`：主頁（關於我們、運作方式、歷屆活動與走讀地圖、研習證明、學會資訊、支持我們、加入我們）
- `bylaws.html`：學會章程與施行細則
- `data/walkmap.json`：走讀地圖的行政區界（內政部村里界，taiwan-atlas）與走讀點位
- `img/`：網站圖片

## 發布到 GitHub Pages

Settings → Pages → Build and deployment → Source 選 **Deploy from a branch**，Branch 選 `main`、資料夾 `/ (root)`，存檔後約一分鐘即可在 `https://<帳號>.github.io/<repo 名稱>/` 看到網站。

> 地圖需透過網址開啟（GitHub Pages 或本機伺服器），直接雙擊 `index.html` 會因瀏覽器限制讀不到 `data/walkmap.json`。
