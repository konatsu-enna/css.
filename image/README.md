/* 古風配色與宣紙背景風格 */
body {
    font-family: "Kaiti SC", "KaiTi", "標楷體", "DFKai-SB", "Noto Serif TC", serif;
    color: #2b2b2b;
    background-color: #f7f4ed; /* 米黃宣紙底色 */
    max-width: 850px;
    margin: 20px auto;
    padding: 30px;
    line-height: 1.8;
    border: 8px double #5c3a21; /* 古木雙框線 */
    box-shadow: 0 0 15px rgba(0, 0, 0, 0.15);
}

/* 頂部大標題（仿古典圖書卷軸標題） */
h1 {
    text-align: center;
    color: #8c2323; /* 赭紅 / 硃砂色 */
    font-size: 2.2em;
    letter-spacing: 4px;
    margin-bottom: 25px;
    padding-bottom: 15px;
    border-bottom: 2px solid #8c2323;
    text-shadow: 1px 1px 1px #d4c5b3;
}

/* 報導目錄 / 古風選單 */
nav {
    background-color: #efe9dc;
    border: 1px solid #c4b59d;
    padding: 15px;
    margin-bottom: 30px;
    border-left: 5px solid #8c2323;
}
nav strong {
    color: #8c2323;
    font-size: 1.1em;
    letter-spacing: 2px;
    display: block;
    margin-bottom: 10px;
}
nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    flex-wrap: wrap;
    gap: 12px 20px;
}
nav a {
    color: #4a3728;
    text-decoration: none;
    font-weight: bold;
    border-bottom: 1px dotted #8c2323;
    padding-bottom: 2px;
    transition: all 0.2s;
}
nav a:hover {
    color: #8c2323;
    background-color: #e5dbc9;
}

/* 各區塊小標題（仿卷軸印章點綴） */
h2 {
    color: #8c2323;
    font-size: 1.4em;
    border-bottom: 1px solid #a8967d;
    padding-bottom: 6px;
    margin-top: 35px;
    margin-bottom: 15px;
    letter-spacing: 1px;
}

/* 文字與連結 */
p, li {
    font-size: 1.05em;
}
a {
    color: #7a2020;
}
a:hover {
    color: #aa2222;
}

/* 表格古風木格風格 */
table {
    width: 100%;
    border-collapse: collapse;
    margin: 20px 0;
    background-color: #faf7f2;
}
th, td {
    border: 1px solid #8c765c;
    padding: 10px;
    text-align: left;
}
th {
    background-color: #e2d7c3;
    color: #5c2323;
    font-weight: bold;
}

/* 圖片古風框框處理 */
img {
    max-width: 100%;
    height: auto;
    display: block;
    margin-bottom: 8px;
    border: 3px solid #d4c5b3;
    box-shadow: 2px 2px 5px rgba(0,0,0,0.1);
}
.img-caption {
    font-size: 0.9em;
    color: #555;
    margin-bottom: 15px;
}

/* 影音與地圖框架 */
.responsive-embed {
    position: relative;
    padding-bottom: 56.25%;
    height: 0;
    overflow: hidden;
    margin-top: 12px;
    margin-bottom: 25px;
    border: 3px solid #c4b59d;
}
.responsive-embed iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0;
}
# Vibe Coding 專案指令紀錄

本專案使用 AI (Vibe Coding) 輔助完成。以下為開發過程中使用的 Prompt 指令：

## 使用的 Prompt 指令

1. **建立網站架構：**
   > "請幫我建立一個包含完整 SEO Meta 標籤、CSS Grid 佈局以及 RWD 響應式設計的 HTML 範本。"

2. **樣式切割與分離：**
   > "請將 CSS 樣式獨立抽離成單獨的 css/style.css 檔案，並確保手機版與電腦版皆能正常顯示。"

## GitHub 專案連結
- GitHub 儲存庫：[請在建立 GitHub 後將網址貼在這裡]
