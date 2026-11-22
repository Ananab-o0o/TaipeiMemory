# 台北記憶導覽｜GitHub Pages 網站檔案

這份網站包含首頁、五個景點頁、手機版樣式、五站集章，以及 NFC 網址清單。

## 上傳到你現有的 GitHub Repository

你的 Repository：`TaipeiMemory`

1. 解壓縮這個 ZIP。
2. 打開解壓縮後的 `TaipeiMemory_site` 資料夾。
3. 將裡面的**所有檔案與資料夾**上傳到 GitHub Repository 的最外層（root）。
4. GitHub 若詢問是否取代原本的 `index.html`，選擇確認取代。
5. 按下 `Commit changes`。
6. 確認 `Settings → Pages` 仍是 `Deploy from a branch`、`main`、`/(root)`。
7. 等待 GitHub Pages 部署完成，再開啟首頁。

## 正確的 Repository 結構

```text
TaipeiMemory/
├── index.html
├── spot1.html
├── spot2.html
├── spot3.html
├── spot4.html
├── spot5.html
├── NFC網址清單.txt
├── README_上傳教學.md
└── assets/
    ├── css/
    │   └── style.css
    └── js/
        └── app.js
```

## 網站網址

首頁：https://ananab-00o.github.io/TaipeiMemory/

五個 NFC 標籤網址已整理在 `NFC網址清單.txt`。將每一個網址分別寫入一張 NFC 標籤即可。

## 五站順序與資料說明

1. 林復振商行：迪化街一段 105 號，1853 年起。
2. 李亭香：迪化街一段 309 號，1895 年創立。
3. 老綿成燈籠店：迪化街一段 298 號，1915 年創立。
4. 食連動魚丸（原味香魚丸）：迪化街一段 337 號，1961 年起家。
5. 林華泰茶行：重慶北路二段 193 號，1883 年創立。

**資料校正提醒：** 前面討論曾將「進成魚丸」寫為 1916 年創立，但目前找到的可靠公開資料不足以支持這個年份。本版改採臺北市商業處及店家官方資料可核對的「食連動魚丸（原味香魚丸）」，其前身自 1961 年起家。若你希望保留進成魚丸，請先實地確認店家故事與年份，再更新資料。

## 集章功能

集章紀錄使用瀏覽器 `localStorage`，只存在目前使用者的這台裝置與瀏覽器，不會自動跨手機同步，也不是防作弊的正式簽到系統。

## 圖片與訪談

目前版本以文字、色塊與符號建立完整可用版型，沒有擅自抓取未授權的店家照片。建議實地拍攝店面、商品與街景，取得店家同意後，再加入頁面。若要加入訪談，請先徵求受訪者同意。

## 來源

- 林復振商行官方網站：https://www.linfuzhen.com/about
- 李亭香官方門市資訊：https://lee-cake.com/locations
- 臺北旅遊網（李亭香）：https://travel.taipei/zh-tw/pictorial/article/7646
- 臺北旅遊網（老綿成）：https://www.travel.taipei/file/14115/
- 臺北市商業處（食連動魚丸）：https://www.tcooc.gov.taipei/cp.aspx?n=8D0974959002A45D
- 食連動魚丸官方網站：https://fishball1961.com/about.php
- 國家文化記憶庫（林華泰茶行）：https://tcmb.culture.tw/zh-tw/detail?id=601589&indexCode=Culture_Place
- 文化部文化資產局（林華泰茶行）：https://nchdb.boch.gov.tw/assets/overview/historicalBuilding/20160822000001

店家營業時間可能調整，實際走訪前請查看店家最新公告。
