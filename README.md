# 玄奘之路戈壁挑戰賽 · 第二十一屆

**Ultra Gobi® 121km · 2026 · 甘肅瓜州**

四天三夜穿越莫賀延磧戈壁的賽事路線總覽頁面，包含：

- 每日路線、里程、地形說明
- 爬升 / 下降高程估算（基於 SRTM 地形模型）
- 四日全程海拔變化圖
- 每段 OpenStreetMap 實際地圖
- A 隊 / 沙克爾頓獎關門時間

## 查看頁面

👉 **https://<你的GitHub帳號>.github.io/<repo名稱>**

## 如何部署到 GitHub Pages

1. 在 GitHub 建立新 repository（可命名為 `gobi-race` 或任意名稱）
2. 上傳 `index.html`（與本 README）到 `main` branch
3. 前往 **Settings → Pages**
4. Source 選 **Deploy from a branch**，Branch 選 `main`，資料夾選 `/ (root)`
5. 儲存後稍等 1–2 分鐘，即可從上方連結訪問

## 賽段資訊

| 日期 | 賽段 | 里程 | 累計爬升 | 累計下降 |
|------|------|------|---------|---------|
| 10/1 體驗日 | 阿育王寺 → 常樂驛 | 29.06 km | ~180m | ~248m |
| 10/2 第一日 | 常樂驛 → 崑崙障 | 31.97 km | ~140m | ~190m |
| 10/3 第二日 | 崑崙障 → 黃谷驛 | 33.69 km | ~290m | ~430m |
| 10/4 第三日 | 黃谷驛 → 戈壁清泉 | 27.00 km | ~250m | ~530m |
| **全程** | | **121.72 km** | **~860m** | **~1400m** |

> ⚠️ 爬升/下降為 SRTM 地形模型估算值，非官方數據。主辦單位不公開 GPX 路線圖。

## 技術說明

- 純靜態 HTML + CSS（無框架、無 JS 依賴）
- 字體：Google Fonts（Noto Serif SC, Cinzel, Noto Sans SC），含系統字體 fallback
- 地圖：OpenStreetMap embed（無需 API key）
- 高程圖：SVG 手繪，基於地形估算

---

*資料來源：鎖陽城海拔 1358m（中新網甘肅）、各段地形參考歷屆參賽者紀錄及 SRTM 30m DEM。*
