
# 點數兌換流程（DBSAFER 獎勵制度內部作業頁）

本專案為 DBSAFER 推廣活動中，針對「經銷商點數兌換作業」所設計的流程指引頁面，提供內部業務與合作夥伴一目瞭然的操作步驟。

## 🎯 功能簡介

- ✅ 視覺化卡片流程（共 5 步驟）
- ✅ 各階段負責人、文件下載、完成時限一目了然
- ✅ 響應式設計，支援桌機與行動裝置
- ✅ 無需伺服器、可直接佈署至 GitHub Pages

## 📁 專案結構

```
point-exchange-flow/
├── index.html          # 主畫面，可直接開啟或部署
└── README.md           # 本說明文件
```

## 🚀 快速開始

### 本地預覽

1. 下載或 clone 本專案：
   ```bash
   git clone https://github.com/your-org/point-exchange-flow.git
   ```
2. 使用瀏覽器開啟 `index.html` 即可瀏覽

### GitHub Pages 佈署方式

1. 將專案上傳至 GitHub Repository
2. 進入 Repository → `Settings` → `Pages`
3. Source 設定為 `Deploy from a branch`，分支選擇 `main`，路徑選擇 `/ (root)`
4. 儲存後稍待數分鐘，即可透過下列網址存取：
   ```
   https://your-username.github.io/point-exchange-flow/
   ```

## 🔧 技術架構

- 前端框架：純 HTML + TailwindCSS（CDN）
- 圖示系統：Lucide Icons（CDN）
- 不依賴 npm、Node.js 或 Vite，輕量部署無壓力

## 📌 使用須知

- 所有內容靜態呈現，適合用於 SOP、教育訓練或內部溝通
- 如需擴充中英切換、動畫或互動功能，可另洽技術支援

## 📞 聯絡資訊

- 內容規劃：Gini  
- UI/技術支援：ChatGPT x GitHub Pages
