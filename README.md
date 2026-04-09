# 臺灣掃帚 Taiwan Broom

**臺灣掃帚所述說的故事**
*A single-page exhibition website for the Taiwan Broom collection, presented at Tokyo.*

---

## 關於計劃 About

這個臺灣掃帚的蒐集計畫，源自於長期在臺灣各地進行的田野調查——發現許多鄉鎮不使用都市中便宜耐用的塑膠掃帚，而是就地取材，用當地盛產植物做出「自然掃帚」。這些掃帚不只是清潔工具，更是每個地方的植物、人文、歷史的載體。

2017年提出的構想，受日本知名採購人山田遊先生邀請，於東京 **(PLACE) by method** 畫廊正式展出。

This project documents 9 types of handcrafted natural brooms from across Taiwan — from temple ritual brooms to indigenous mountain-palm brooms to nearly-lost village industries. Each broom tells a local story.

---

## 網站結構 Site Structure

| 區段 | 內容 |
|------|------|
| **區段 1** | 全版主視覺橫幅 |
| **區段 2** | 計劃理念文字介紹 |
| **區段 3** | 9 種掃帚縮圖無縫橫移輪播；滑鼠移入換顯細部圖（淡入＋微放大），點擊跳至對應介紹 |
| **區段 4** | 臺灣傳統手工掃帚地理分佈圖；各類掃帚圖文詳細介紹（含產地、手作師傅），圖片自動慢速輪替 |

---

## 收錄掃帚種類 Broom Types

| # | 名稱 | 產地 | 手作師傅 |
|---|------|------|----------|
| 01 | 槺榔掃帚 | 嘉義縣朴子市 | 涂梅花 |
| 02 | 稻草掃帚 | 宜蘭縣冬山鄉 | 林秋女、藍豐穆 |
| 03 | 高粱掃帚 | 臺東縣東河鄉／金門烈嶼 | （臺東）林統山、黃貴明、黃新玉／（金門）莊扶 |
| 04 | 地膚草掃帚 | 彰化縣福興鄉 | 林振棟、黃張環 |
| 05 | 貴黍掃帚 | 嘉義縣六腳鄉 | 呂保宜、呂春梅、楊福藏 |
| 06 | 山棕掃帚 | 高雄市美濃區 | 羅元鴻、蔡佳蓉 |
| 07 | 山棕嫩葉掃帚 | 南投縣信義鄉 | Sa Vungaz（伍阿現） |
| 08 | 蘆竹掃帚 | 桃園縣平鎮區 | 曾宏凱、曾義深 |
| 09 | 芒草掃帚 | 嘉義縣樟樹湖 | 簡黃秀切 |

---

## 技術 Tech

純 HTML / CSS / JavaScript，無框架依賴。

- **字型**：Noto Serif TC（標題）、Noto Sans TC（內文）via Google Fonts
- **區段 3**：CSS `@keyframes` 無縫 marquee；JS 動態複製節點；hover 淡入細部圖（`opacity` transition）＋微放大（`scale`）；click 平滑滾動至對應掃帚介紹
- **區段 4**：`IntersectionObserver` 滾動淡入；每個掃帚的多張圖片以 `setInterval` 慢速淡入淡出輪替；地理分佈圖以 `object-fit: contain` 保持原始比例
- **視覺風格**：參考 Maison Margiela Folders 美學——奶白底色、極簡排版、大量留白

---

## 展覽資訊 Exhibition

**2026.5.7 (Fri) – 5.24 (Sun)**
台湾の箒作り — 掃除する日常の風景 —

**(PLACE) by method**
〒150-0011 東京都渋谷区東1-3-1 カミニート14号
[placebymethod.com](https://placebymethod.com/)

---

## 製作團隊 Credits

**特別感謝** 臺灣在地師傅（依地理排序）
曾宏凱、曾義深、田俊雄、田煥禎、張煥金、Sa Vungaz（伍阿現）、林振棟、黃張環、呂保宜、呂春梅、涂梅花、楊福藏、簡黃秀切、林秋女、藍豐穆、羅元鴻、蔡佳蓉、林統山、黃貴明、黃新玉、莊扶

**企劃** 支流有限公司
採訪　王威智、陳玲芳、陳培瑜、鍾仁嫻
攝影　劉鎮豪、曾雅鈺
特約撰文　林雅雯
美術設計　黃瑪琍
總編輯　周易正
展覽企劃籌備　鄭湘榆

*2018年文化部推動國家文化記憶庫計畫補助專案*
