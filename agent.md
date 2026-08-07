# 專案紀錄

> 更新日期：2026-08-07  
> 專案類型：Bootstrap 5 響應式旅遊廣告銷售頁

## 專案概述

本專案為「華梵旅遊」日韓客製深度旅遊銷售頁，依據 `0-UIUX.png` 設計稿切版。網站採用單頁式架構，以深藍、金色及米白為主視覺，目標是引導訪客填寫免費旅遊規劃預約表單。

## 專案結構

```text
website/
├── index.html       # 銷售頁、樣式與互動程式
├── agent.md         # 專案紀錄
└── images/
    ├── banner-1.jpg
    ├── banner-2.jpg
    ├── banner-3.jpg
    ├── banner-4.jpg
    ├── banner-5.jpg
    └── banner-6.jpg
```

## 使用技術

- HTML5 與響應式語意標記
- Bootstrap 5.3.3（jsDelivr CDN）
- Bootstrap Icons 1.11.3（jsDelivr CDN）
- Google Fonts：Noto Serif TC、Noto Sans TC
- 原生 JavaScript
- 自訂 CSS，直接置於 `index.html`

## 頁面區塊

1. 固定式響應導覽列
2. 主視覺與行動呼籲按鈕
3. 旅遊規劃痛點卡片
4. WHY／HOW／WHAT 客製服務價值
5. 小資蜜月、小家庭樂齡、企業團體三種方案
6. 專屬企劃、無購物站、在地深度、全程支援特色
7. 免費一對一預約表單
8. 頁尾與回到頁首按鈕

## 圖片使用

| 圖片 | 用途 |
| --- | --- |
| `banner-4.jpg` | 首屏主視覺 |
| `banner-6.jpg` | 小資／蜜月方案、預約區背景 |
| `banner-3.jpg` | 小家庭／樂齡方案 |
| `banner-2.jpg` | 企業團體方案 |
| `banner-1.jpg`、`banner-5.jpg` | 保留素材，目前未使用 |

## 互動功能

- 導覽連結使用平滑捲動前往對應區塊。
- 行動版導覽選單在點擊連結後自動收合。
- 預約表單使用瀏覽器必填驗證。
- 表單通過驗證後顯示 Bootstrap Toast 成功訊息並清空欄位。
- 目前表單僅做前端示範，尚未串接後端、CRM 或郵件服務。

## 執行方式

```bash
python3 -m http.server 8000
```

開啟 `http://localhost:8000/`。網站需要網路連線，以載入 Bootstrap、圖示及 Google Fonts。

## 後續建議

1. 串接預約表單 API，並加入錯誤處理與防垃圾訊息機制。
2. 補上正式公司資訊、聯絡方式、隱私權政策與服務條款。
3. 上線前壓縮 JPEG 圖片並提供 WebP／AVIF，以改善載入效能。
4. 加入 GA4、廣告轉換事件與表單送出追蹤。
5. 進行 Chrome、Safari、Firefox 與實機行動裝置測試。
6. 若需離線或內網使用，將 CDN 資源改為本機檔案。

## 紀錄歷程

| 日期 | 紀錄 |
| --- | --- |
| 2026-08-07 | 初次盤點原始 Bootstrap 範例頁。 |
| 2026-08-07 | 依 UIUX 設計稿重建完整響應式旅遊銷售頁，覆蓋原 `index.html`。 |

## Github推送地址
USER NAME:breathtiger
專案名稱：Huafantravel-20260807
HTTPS:https://github.com/breathtiger/Huafantravel-20260807.git
SSH:git@github.com:breathtiger/Huafantravel-20260807.git

## Github發布網址
https://breathtiger.github.io/Huafantravel-20260807/
