東京秋日 5D4N｜V6.2 天氣修正版

本版針對 Cloudflare「Upload your static files」部署方式調整。
天氣資料改由瀏覽器直接向 Open-Meteo 取得，不再依賴 /api/weather 路由。

內容：
- 2026/10/26～10/30 東京 5 日行程
- iPhone 響應式版面
- 東京即時天氣與未來 16 天預報（接近出發日期後會出現 10/26～10/30 的逐日預報）
- 日圓／台幣換算、旅費紀錄、備忘、地圖、打包清單
- PWA manifest 與 service worker

部署：
在 Cloudflare Workers 和 Pages → 建立應用程式 → Upload your static files，上傳本資料夾內全部 6 個檔案後部署。
