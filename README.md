# **Flip Clock Screensaver (翻頁時鐘螢幕保護程式)**

這是一個基於 Web 技術 (HTML, CSS, JavaScript) 開發的全螢幕翻頁時鐘，設計作為螢幕保護程式使用。具有優雅的翻頁動畫、純黑背景（適合 OLED 螢幕），以及使用者可自訂的設定。

## **✨ 特色 (Features)**

* **經典翻頁效果**：使用 CSS 3D Transforms 模擬真實機械鐘的翻頁動畫。  
* **響應式設計**：字體與佈局會根據視窗大小自動調整，支援各種解析度。  
* **全螢幕模式**：點擊畫面任意處即可切換全螢幕，提供沉浸式體驗。  
* **自訂設定**：  
  * 🌗 **深色/淺色模式**：可切換 Dark Mode (預設) 與 Light Mode。  
  * 🕒 **時間格式**：支援 12 小時制 (AM/PM) 與 24 小時制切換。  
* **自動儲存**：設定會自動儲存在瀏覽器的 localStorage 中，下次開啟時自動套用。  
* **閒置隱藏**：滑鼠靜止 3 秒後自動隱藏游標，避免干擾畫面。

## **🚀 如何使用 (Usage)**

### **方法 1：直接開啟**

1. 下載本專案中的 flip\_clock\_screensaver.html (建議重新命名為 index.html)。  
2. 直接用瀏覽器 (Chrome, Edge, Safari, Firefox) 開啟該檔案即可。

### **方法 2：部署到 GitHub Pages (推薦)**

1. 將本專案上傳至您的 GitHub Repository。  
2. 到 Repository 的 **Settings** \> **Pages**。  
3. 在 **Branch** 選擇 main (或 master) 並儲存。  
4. 幾分鐘後，GitHub 會提供一個網址，您就可以在任何裝置上存取這個時鐘了。

## **🛠️ 技術細節 (Tech Stack)**

* **HTML5**: 語意化標籤結構。  
* **Tailwind CSS (CDN)**: 快速處理 Flexbox 佈局與 RWD 樣式。  
* **Vanilla JavaScript**: 處理時間邏輯、DOM 操作與 LocalStorage 存取，無須編譯即可運作。  
* **Google Fonts**: 使用 Roboto Mono 字體，確保數字顯示風格統一。

## **📝 授權 (License)**

MIT License. 歡迎自由修改與使用。