---
isChild: true
title: 好處
anchor: templating_benefits
---

## 好處 {#templating_benefits_title}

使用樣板的主要好處是可以將展現邏輯與應用程式的其他部份明確分離。樣板的唯一責任便是顯示轉化過的內容。它不負責查詢、保存資料或是其他複雜的任務。這促成了更乾淨、更具可讀性的程式碼，在開發者專注伺服器端程式（控制器、模型），而設計師負責用戶端程式（網頁標記）的團隊協作環境中，樣板導入尤其有用。

樣板同時也改善了前端程式碼的組織架構。一般而言，樣板放置在「視圖」的資料夾中，每個樣板定義在各自獨立的檔案中。這種方式鼓勵程式碼重用，它將大區塊的程式碼分為較小、可重用的段落，通常稱作局部樣板 (partials) 。舉例來說，網站的頭、尾區塊可以各自定義為樣板，之後將它們置於每一個頁面樣板的上、下位置。

最後，端視你所使用的函式庫，樣板可以透過自動逸脫使用者產出內容，帶來更多的安全性。有些函式庫甚至提供沙箱機制，樣板設計師只能使用在白名單中的變數和函式。
