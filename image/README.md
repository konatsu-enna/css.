# 🌐 台中東協廣場導覽網站 (Vibe Coding 專案)

本專案為網頁設計課程作業，透過 AI 輔助 (Vibe Coding) 進行開發，符合完整 SEO、CSS Grid System、RWD 手機自適應等規範。

## 🛠️ Vibe Coding 指令 (Prompt) 記錄

在開發過程中，向 AI 發出了以下核心指令：

1. **結構與 SEO 建立：**
   > "請幫我建立一個具備完整 SEO Meta 標籤（title, description）、語意化標籤與導覽列的東協廣場介紹 HTML 頁面。"
2. **CSS 切割與資料夾管理：**
   > "請將所有行內與內嵌的 CSS 樣式抽離，獨立成 `css/style.css` 檔案；圖片資源統一規劃至 `images/` 資料夾中。"
3. **Grid System 與 RWD 響應式優化：**
   > "請在 CSS 中使用 CSS Grid System 網格系統，並透過 `@media` 查詢確保在手機、平板與電腦等手持裝置上皆能完整、美觀地顯示資訊。"

## 📂 專案檔案架構
```text
.
├── index.html        # 網站首頁
├── README.md         # 專案說明與 Vibe Coding 紀錄
├── css/
│   └── style.css     # 獨立樣式表
└── images/           # 圖片素材資料夾
