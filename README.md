# 地點範圍搜尋工具

一個簡單且精準的網頁工具，用於在地圖上標註特定地點及其周邊半徑範圍。

## 🚀 功能特色
- **地址搜尋**：支援地址與經緯度搜尋，自動定位中心點。
- **預設範圍**：自動產生 500m、1000m、2000m 的灰色中空圓圈。
- **自定義半徑**：可手動輸入半徑，產生帶有藍色標籤的圓圈。
- **自動縮放**：地圖會根據圓圈大小自動調整視野。
- **精準截圖**：一鍵下載 600x600 的正方形 PNG 圖片，檔名包含時間戳記。
- **快捷操作**：支援 `Ctrl + Enter` 快速啟動搜尋。

## 🛠 使用技術
- [Leaflet.js](https://leafletjs.com/) - 地圖渲染引擎
- [OpenStreetMap / CARTO](https://carto.com/) - 地圖圖磚來源
- [dom-to-image](https://github.com/tsayen/dom-to-image) - 網頁轉圖片工具
- [Nominatim API](https://nominatim.org/) - 地理座標轉換服務

## 📂 如何發布至 GitHub Pages
1. 將 `index.html` 上傳至 GitHub 儲存庫。
2. 進入 **Settings > Pages**。
3. 選擇 `main` 分支並點擊 **Save**。
4. 稍候片刻即可透過產生的網址使用。