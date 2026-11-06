# 好友德州撲克（虛擬籌碼）

## 本機測試
安裝 Node.js 18+，在此資料夾執行：

```bash
npm install
npm start
```

開啟 http://localhost:3000 。

## 分享給朋友
將整個專案上傳 GitHub，至 Render.com 建立 Web Service，連結儲存庫：
- Build command: `npm install`
- Start command: `npm start`
- 使用支援持續執行 Node.js 與 WebSocket 的服務方案

部署完成後，把 `https://你的網址/?room=房間代碼` 分享給朋友。不可只把 HTML 放到靜態網頁主機。

## 注意
此版本為多人連線原型，沒有帳號登入、斷線重連、持久儲存、下注計時器或防作弊稽核。重新啟動伺服器會清空房間。只適合朋友間使用虛擬籌碼，不支援真實金錢。
