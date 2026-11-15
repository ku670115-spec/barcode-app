# 條碼查詢 App

7-11 門市用的條碼查詢工具：打品名或品號就能叫出商品條碼，直接給收銀機刷。

- 網頁版：https://bk-barcode.netlify.app
- 安裝頁（Android／iPhone）：https://bk-barcode.netlify.app/download.html

## 功能
- 🔍 搜尋品名、品號、條碼（可用空白分隔多個關鍵字）
- 📷 相機掃描條碼
- 🔲 點商品放大條碼，左右滑可換下一個
- ⭐ 收藏、最近查看
- ⏰ 即期參考：依月份排列、標示剩幾天
- 🏷 活動篩選、隱藏已下架
- ➕ 自己補商品（只存在自己手機）＋備份還原

## 資料來源
商品資料即時讀取 `https://bk-bc.github.io/Barcode/new.csv`（只讀取，不會修改對方資料）。

## 檔案說明
| 檔案 | 用途 |
| --- | --- |
| `index.html` | 主程式（網頁版／App 共用） |
| `download.html` | 安裝說明頁 |
| `barcode-app.apk` | Android 安裝檔 |
| `manifest.json`、`icon-*.png`、`apple-touch-icon.png` | 加入主畫面用的設定與圖示 |
| `_headers` | Netlify 下載 APK 用的設定 |
| `android/` | Android App 原始碼（WebView 外殼，開啟網頁版） |

> Android 簽章金鑰不放在這個公開倉庫。
