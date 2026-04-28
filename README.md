# 臺灣掃帚 Taiwan Broom / 台湾の箒

**臺灣掃帚所述說的故事**
*掃除する日常の風景 — A single-page exhibition website for the Taiwan Broom collection, presented in Tokyo.*

---

## 關於計劃 About

這個臺灣掃帚的蒐集計畫，源自於長期在臺灣各地進行的田野調查——發現許多鄉鎮不使用都市中便宜耐用的塑膠掃帚，而是就地取材，用當地盛產植物做出「自然掃帚」。這些掃帚不只是清潔工具，更是每個地方的植物、人文、歷史的載體。

2017年提出的構想，受日本知名採購山田遊先生邀請，於東京 **(PLACE) by method** 畫廊正式展出。許多師傅因為這次特別的邀請而重新拿起工具、走入山林，讓這些日常美學重新被人看見。

---

## 展覽資訊 Exhibition Info

**2026.5.8 (Fri) – 5.24 (Sun)**
**台湾の箒作り — 掃除する日常の風景 —**

**地點 Venue:**
**(PLACE) by method**
〒150-0011 東京都渋谷区東1-3-1 カミニート14号
[placebymethod.com](https://placebymethod.com/)

---

## 網站特點 Features

- **多語系支持 (i18n)**：完整支援 **繁體中文**、**English**、**日本語**，一鍵無縫切換。
- **響應式設計 (RWD)**：針對手機與平板深度優化，提供流暢的行動端體驗。
- **Hero 輪播**：Section 1 三圖緩慢交叉淡入輪播（24 秒週期），手機版各自優化裁切位置。
- **工藝展示**：Section 5 以壓縮 MP4 影片呈現 6 種掃帚製作工藝，無限橫向輪播，含緩慢橫移視差效果；影片進入視野才載入播放，節省行動端頻寬。
- **捲動動畫**：Section 2 文字進入視野時依序 fade-up 浮現。
- **效能優化**：英雄圖壓縮至 935KB、Section 3/4 圖片壓縮、MP4 影片壓縮約 50%、影片懶載入、`preload="none"`、`fetchpriority="high"`。
- **Footer**：東京展覽欄位含山田遊三語簡介（JS 動態對齊）；Facebook 連結與版權列；手機版自動調整欄位順序。

---

## 網站結構 Site Structure

| 區段 Section | 內容 Description |
| :--- | :--- |
| **Section 1** | 三圖緩慢交叉淡入輪播主視覺 (Hero Crossfade Slideshow) |
| **Section 2** | 計劃理念文字介紹 (Project Philosophy) |
| **Section 3** | 東京展覽引導：展期、地點、Google Maps 連結 (Tokyo Exhibition Guide) |
| **Section 4** | 9 種掃帚縮圖無縫輪播 (Seamless Marquee) |
| **Section 5** | 掃帚詳細介紹與圖文故事 (Detailed Stories with Slideshow) |
| **Section 6** | 工藝展現 MP4 無限橫向輪播，6 種掃帚製作影片 (Craftsmanship Marquee) |
| **Modal** | 詳細介紹小卡與高解析影像藝廊 (Deep Dive Gallery) |

---

## 收錄掃帚種類 Taxonomy

| # | 名稱 (Trad. Chinese / English / 日本語) | 產地 Origin |
|:---:|:--- |:--- |
| 01 | **槺榔掃帚** / Date palm / カンラン | 嘉義朴子 |
| 02 | **稻草掃帚** / Straw / 稲わら | 宜蘭冬山／雲林莿桐 |
| 03 | **高粱掃帚** / Sorghum / モロコシ | 臺東東河 |
| 04 | **地膚草掃帚** / Kochia / ホウキグサ | 彰化福興 |
| 05 | **貴黍掃帚** / Millet / キビ | 嘉義六腳 |
| 06 | **山棕掃帚** / Arenga / クロツグ | 高雄美濃 |
| 07 | **山棕嫩葉掃帚** / Tender leaves / 若葉 | 南投信義 |
| 08 | **蘆竹掃帚** / Arundodis / ダンチク | 桃園平鎮 |
| 09 | **芒草掃帚** / Miscanthus / ススキ | 嘉義梅山 |

---

## 技術與設計 Tech & Design

- **設計語言**：**Minimalist Exhibition Style** —— 鋁灰與奶白配色、大量留白、無框線 UI。
- **極簡切換**：手機版語言切換鈕採用絕對定位，避免滾動遮擋；彈窗按鈕避位優化。
- **渲染與效能**：純 Vanilla JS 驅動，不依賴第三方框架；IntersectionObserver 控制影片與動畫時機，減少不必要的資源消耗。
- **觸控優化**：手機版跑馬燈點擊不暫停（僅桌機 hover 暫停），觸控體驗流暢。

---

## 製作團隊 Credits

**特別感謝** 臺灣在地師傅（依地理排序）
曾宏凱、曾義深、田俊雄、田煥禎、張煥金、Sa Vungaz（伍阿現）、林振棟、黃張環、鍾三才、呂保宜、呂春梅、涂梅花、楊福藏、簡黃秀切、林秋女、藍豐穆、羅元鴻、蔡佳蓉、林統山、黃貴明、黃新玉、莊扶

**企劃** 支流有限公司
- **採訪/攝影/撰文**：王威智、陳玲芳、陳培瑜、鐘仁嫻、劉鎮豪、曾雅鈺、林雅雯
- **美術設計**：謝捲子（主視覺＆周邊）、黃瑪琍（書籍設計）| **總編輯**：周易正 | **展覽籌備**：鄭湘榆

*2018年文化部推動國家文化記憶庫計畫補助專案*
