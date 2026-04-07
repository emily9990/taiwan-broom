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
| **區段 3** | 9 種掃帚縮圖無縫橫移輪播 |
| **區段 4** | 各類掃帚圖文詳細介紹，圖片自動慢速輪替 |

---

## 收錄掃帚種類 Broom Types

| # | 名稱 | 特色 |
|---|------|------|
| 01 | 槺榔掃帚 | 臺灣特有種，廟宇儀式專用，被視為具有法力 |
| 02 | 稻草掃帚 | 農村文化象徵，用於曬穀場分類而非清潔 |
| 03 | 高粱掃帚 | 金門與東部特產，展現族群不同美學觀 |
| 04 | 地膚草掃帚 | 彰化西勢日治時代產業，現已近乎消失 |
| 05 | 貴黍掃帚 | 源自日本茨城，細緻編織工藝，用於榻榻米空間 |
| 06 | 山棕掃帚 | 僅存於臺灣東部，與原住民文化密切相關 |
| 07 | 山棕嫩葉掃帚 | 山棕的精緻子類，目前僅一位老師傅仍在製作 |
| 08 | 蘆竹掃帚 | 桃園平鎮「掃把庄」的地方特產 |
| 09 | 芒草掃帚 | 漢人、客家人、原住民共同的自然生活智慧 |

---

## 技術 Tech

純 HTML / CSS / JavaScript，無框架依賴。

- **字型**：Noto Serif TC（標題）、Noto Sans TC（內文）via Google Fonts
- **區段 3**：CSS `@keyframes` 無縫 marquee，JS 動態複製節點
- **區段 4**：`IntersectionObserver` 滾動淡入；每個掃帚的多張圖片以 `setInterval` 慢速淡入淡出輪替
- **視覺風格**：參考 Maison Margiela Folders 美學——奶白底色、極簡排版、大量留白

---

## 展覽資訊 Exhibition

**(PLACE) by method**
〒150-0011 東京都渋谷区東1-3-1 カミニート14号
[placebymethod.com](https://placebymethod.com/)

---

## 製作團隊 Credits

**特別感謝** 臺灣在地師傅（依地理排序）
曾宏凱、曾義深、田俊雄、田煥禎、張煥金、Sa Vungaz (伍阿現)、林振棟、黃張環、呂保宜、呂春梅、涂梅花、楊福藏、簡黃秀切、林秋女、藍豐穆、林統山、黃貴明、黃新玉、莊扶

**企劃** 支流有限公司
採訪　王威智、陳玲芳、陳培瑜、鍾仁嫻
攝影　劉鎮豪、曾雅鈺
特約撰文　林雅雯
美術設計　黃瑪琍
總編輯　周易正

*2018年文化部推動國家文化記憶庫計畫補助專案*
