# Gemini Certification for Educators - 練習題庫

<div align="center">

![Gemini Certification](https://img.shields.io/badge/Gemini-Certification-blue?style=for-the-badge)
![Questions](https://img.shields.io/badge/題目數量-52題-green?style=for-the-badge)
![Language](https://img.shields.io/badge/語言-中英雙語-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

**完整的 Google Gemini 教育認證練習題庫**

[在線體驗](#) | [功能介紹](#功能特色) | [使用說明](#使用說明)

</div>

---

## 📖 項目簡介

這是一個專為準備 **Google Gemini for Educators Certification** 認證考試而設計的互動式練習題庫。包含 52 道精心設計的題目,涵蓋認證考試的所有核心知識領域。

### 🎯 適用對象

- 準備參加 Gemini 教育認證考試的教師
- 想要深入了解 Gemini 在教育應用的教育工作者
- 學習 AI 輔助教學工具的學校管理者
- 對生成式 AI 在教育領域應用感興趣的任何人

---

## ✨ 功能特色

### 📚 題庫內容
- **52 道完整題目**
  - 🔵 單選題: 24 題 (46%)
  - 🟢 多選題: 13 題 (25%)
  - 🟡 是非題: 15 題 (29%)

### 🌍 中英雙語
- 每道題目都提供**完整中英文對照**
- 一鍵切換語言,方便不同背景學習者
- 支援英語學習和專業術語掌握

### 🎨 精美設計
- 現代化漸層配色設計
- 流暢的動畫效果和過渡
- 響應式設計,支援手機、平板、電腦

### 📊 智能統計
- 即時答題進度追蹤
- 答對率統計分析
- 詳細的錯題回顧功能
- 分類統計(單選/多選/是非)

### 💡 學習輔助
- 每題都有**詳細中文解析**
- 答對/答錯即時視覺反饋
- 知識領域分類複習
- 可自訂練習題數(10-52題)

---

## 📂 知識領域涵蓋

### 🎯 領域一:理解生成式 AI
- 生成式 AI 基本概念與運作原理
- AI 幻覺(Hallucinations)的定義與識別
- 機器學習與訓練資料集
- Token、參數、上下文窗口概念
- AI 偏見的來源與影響

### 🛠️ 領域二:實施 Gemini
- PARTS 提示詞框架完整應用
- Gems:建立與管理自訂指令
- Canvas:文件協作空間
- Deep Research:深度研究功能
- Guided Learning:對話式學習引導
- Workspace 整合(Docs/Gmail/Slides/Forms)
- Few-shot Learning 技巧

### 🎓 領域三:課堂實作
- 差異化教學材料設計
- NotebookLM 教學應用
- 評量設計與實施
- 教材研究與準備策略
- 工具選擇與應用場景

### ⚖️ 領域四:負責任使用 AI
- 學術誠信與引用規範
- 隱私保護與資料安全
- AI 偏見識別與處理
- 批判性思考培養
- 健康的 AI 使用習慣

---

## 🚀 使用說明

### 在線使用

訪問 [GitHub Pages 鏈接](https://NMAzusa0125.github.io/gemini-quiz/) 即可直接使用

### 本地運行

1. **下載文件**
   ```bash
   git clone https://github.com/你的用戶名/倉庫名稱.git
   cd 倉庫名稱
   ```

2. **開啟網頁**
   - 直接用瀏覽器開啟 `index.html`
   - 或使用本地伺服器:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Node.js
   npx serve
   ```

3. **開始練習**
   - 訪問 `http://localhost:8000`
   - 享受學習! 📚

---

## 🎮 功能導覽

### 主要功能

| 功能 | 說明 |
|------|------|
| 🎲 **開始練習** | 從 52 題中隨機抽取指定數量題目 |
| 🔄 **重新開始** | 重新隨機抽取題目,開始新的練習 |
| 🌐 **語言切換** | 中文/英文即時切換,學習更靈活 |
| 📊 **即時統計** | 追蹤答題進度、正確率、剩餘題數 |
| 💭 **詳細解析** | 每題都有完整中文解析說明 |
| 📝 **錯題回顧** | 完成後可查看所有答錯的題目 |
| 📚 **知識複習** | 按領域分類的知識點總覽 |

### 答題提示

- ✅ **綠色**: 答對了!
- ❌ **紅色**: 答錯了
- ⚠️ **黃色**: 多選題部分正確
- 單選題: 選擇一個最佳答案
- 多選題: 選擇所有正確選項
- 是非題: 判斷正確或錯誤

---

## 🛠️ 技術棧

- **React 18** - UI 框架
- **Babel Standalone** - JSX 編譯
- **CSS3** - 動畫與樣式
- **LocalStorage** - 數據持久化(未來功能)
- **純前端** - 無需後端,完全靜態

---

## 📱 瀏覽器支援

- ✅ Chrome / Edge (推薦)
- ✅ Firefox
- ✅ Safari
- ✅ 移動端瀏覽器

---

## 🤝 貢獻指南

歡迎貢獻新題目或改進建議!

### 添加新題目

1. Fork 這個倉庫
2. 在 `index.html` 的 `allQuestions` 數組中添加新題
3. 確保題目格式正確:
   ```javascript
   {
       id: 53,
       type: "single", // "single", "multiple", "truefalse"
       category: "分類名稱",
       question: "中文題目",
       questionEn: "English question",
       options: ["選項1", "選項2", "選項3", "選項4"],
       optionsEn: ["Option 1", "Option 2", "Option 3", "Option 4"],
       correct: [0], // 正確答案的索引(多選可多個)
       explanation: "中文解析"
   }
   ```
4. 提交 Pull Request

### 報告問題

如果發現:
- 題目錯誤或不準確
- 翻譯問題
- 功能 Bug
- UI/UX 改進建議

請在 [Issues](https://github.com/NMAzusa0125/gemini-quiz/issues) 中提出!

---

## 📜 版本歷史

### v1.0.0 (2025-01-XX)
- ✨ 初始版本發布
- 📚 包含 52 道完整題目
- 🌐 中英雙語支援
- 🎨 精美 UI 設計
- 📊 完整統計功能

---

## 📄 授權

本項目採用 [MIT License](LICENSE) 授權

**自由使用條款:**
- ✅ 可用於個人學習
- ✅ 可用於教學培訓
- ✅ 可自由修改和分發
- ✅ 可用於商業用途

**唯一要求:** 保留原作者署名

---

## 🙏 致謝

- 感謝 Google 提供 Gemini 教育認證計劃
- 感謝所有使用和反饋的教育工作者
- 題目內容基於官方認證考試大綱設計

---

## 📞 聯絡方式

- 📧 Email: kcazusa1225@gmail.com

---

## ⭐ 如果這個項目對你有幫助

請給個 Star ⭐ 支持一下!也歡迎分享給更多需要的教育工作者!

---

<div align="center">

**用 ❤️ 為教育工作者打造**

[回到頂部](#gemini-certification-for-educators---練習題庫)

</div>
