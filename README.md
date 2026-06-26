# 即時同步翻譯機 PWA

多國語言即時翻譯網頁應用，支援安裝到手機主畫面（PWA）。

## 功能

| 功能 | 說明 |
|------|------|
| 🎙️ 語音翻譯 | 即時語音識別 + 同步翻譯 + 語音朗讀 |
| 💬 雙人對話 | A/B 兩人各說母語，自動翻譯給對方 |
| ⌨️ 打字翻譯 | 即時自動翻譯 + 多語同步翻譯 |
| 📸 圖片翻譯 | 拍照 / 上傳圖片 → OCR 識別 → 翻譯 |
| 📝 錄音轉寫 | 語音轉文字，可匯出 .txt |
| 📋 語音摘要 | 錄音後提取關鍵詞、生成重點摘要 |
| 🔲 懸浮翻譯 | 選取任意文字即時翻譯 |
| 🕐 歷史記錄 | 最多 100 筆，支援搜尋 / 收藏 / 匯出 |

## 支援語言

中文（繁體/簡體）、英語、日語、韓語、法語、德語、西班牙語、泰語、越南語、阿拉伯語、葡萄牙語、俄語、義大利語

## 技術

- **翻譯引擎**：[MyMemory API](https://mymemory.translated.net/)（免費）
- **語音識別**：Web Speech API
- **OCR**：[Tesseract.js](https://tesseract.projectnaptha.com/) v5
- **離線支援**：Service Worker
- **安裝**：PWA Manifest

## 使用方式

直接開啟 GitHub Pages 連結，或：

```bash
git clone https://github.com/YOUR_USERNAME/multilingual-translator-pwa
cd multilingual-translator-pwa
# 用任意 HTTP 伺服器開啟 index.html
```

> 建議使用 **Google Chrome** 以獲得最佳語音識別效果。

## 部署

本專案透過 **GitHub Pages** 自動部署，推送到 `main` 分支即生效。

## License

MIT
