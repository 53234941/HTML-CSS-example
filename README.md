# 彈性網站專案

此專案是一個泛用的網站範本，設計目的是易於自訂和擴展。它包含結構化的佈局，並將樣式、腳本和資源分別存放於不同的檔案中。

## 專案結構

```
flexible-website
├── src
│   ├── assets
│   │   ├── css
│   │   │   └── styles.css
│   │   ├── js
│   │   │   └── scripts.js
│   │   └── fonts
│   └── index.html
├── .gitignore
├── package.json
└── README.md
```

## 功能特色

- **響應式設計**：網站採用響應式設計，能適應各種螢幕尺寸。
- **模組化 CSS**：樣式被組織在獨立的 CSS 檔案中，便於維護。
- **JavaScript 互動性**：使用 JavaScript 增強用戶互動性並管理動態內容。
- **字型管理**：可輕鬆將自訂字型新增至 `fonts` 資料夾。

## 安裝方式

1. 複製此專案庫：
   ```
   git clone <repository-url>
   ```
2. 進入專案目錄：
   ```
   cd flexible-website
   ```
3. 安裝相依套件：
   ```
   npm install
   ```

## 使用方式

- 在瀏覽器中開啟 `src/index.html` 以檢視網站。
- 修改 `src/assets/css/styles.css` 以更改樣式。
- 更新 `src/assets/js/scripts.js` 以新增或修改 JavaScript 功能。

## 貢獻

歡迎貢獻！如有任何建議或改進，請提交 Pull Request 或開啟 Issue。

## 授權

此專案採用 MIT 授權條款。