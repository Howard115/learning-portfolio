# 語音翻譯 Chrome extension 開發經驗

## 情境（Situation）
作為一個非英語母語者，我在使用 ChatGPT 等大型語言模型時發現一個普遍問題：這些 AI 工具對英文輸入的響應質量明顯更好，但我在用英文表達時往往不夠流暢。這促使我尋找一個能夠幫助我快速進行中英互譯的工具。

## 任務（Task）
- 開發一個 Chrome extension，能夠將中文語音實時轉換為英文文本
- 提供中英文互譯功能
- 確保用戶體驗流暢，操作簡單直觀
- 支持快捷鍵操作，提高使用效率

## 行動（Action）
- 基於一個 Open Source 項目的基礎代碼，進行了以下改進：
  - 添加了 OpenAI API 支持，實現英譯中功能
  - 增加了快捷鍵支持（Ctrl+R 開始錄音，Ctrl+C 複製文本，Ctrl+B 翻譯/複製中文）
  - 添加了歷史記錄功能，保存最近的翻譯結果
  - 優化了 User Interface，使其更直觀易用

## 結果（Result）
- 成功開發出一個實用的 Chrome extension，能夠滿足日常中英互譯需求
- 通過 Open Source 方式回饋 community，將改進後的代碼發布到 GitHub
- 獲得了實際的 Frontend 開發和 API 集成經驗
- 學習到了 Chrome extension 開發的相關知識，包括：
  - Chrome Storage API 的使用
  - Third-party API 集成
  - UI/UX 設計和交互優化

這個項目不僅解決了我個人的需求，也讓我對 Open Source 有了更深的理解。通過改進既有項目而不是從零開始，我學會了如何在現有代碼基礎上進行優化和創新。 

