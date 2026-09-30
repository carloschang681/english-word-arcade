# Word Arcade 英文單字九宮格

這是一個純靜態英文單字練習遊戲，可以部署到 GitHub Pages，並用 iPhone/iPad 的 Safari 開啟。

## iOS 使用方式

1. 用 Safari 開啟 GitHub Pages 網址。
2. 點分享按鈕。
3. 選「加入主畫面」。
4. 從主畫面打開後會以接近 App 的全螢幕模式使用。

## GitHub Pages 部署

1. 建立 GitHub repository。
2. 上傳此資料夾內全部檔案。
3. 到 repository 的 `Settings > Pages`。
4. Source 選 `Deploy from a branch`。
5. Branch 選 `main`，資料夾選 `/root`。
6. 等待 GitHub 產生網址。

## 檔案

- `index.html`: 遊戲主程式。
- `manifest.webmanifest`: iOS/行動裝置安裝資訊。
- `sw.js`: 離線快取。
- `icon.svg`: App 圖示。
