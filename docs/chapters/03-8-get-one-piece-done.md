---
layout: default
title: 第八章：開始構建 | Shape Up 繁體中文翻譯
---

# 第八章：開始構建

當一個團隊開始一個新的週期時，他們面臨著一個巨大的挑戰：如何開始？提案給了他們方向，但沒有詳細說明如何實現解決方案。在這一章中，我們將討論團隊如何開始構建過程。

## 讀取提案

團隊的第一步是仔細閱讀提案。提案包含了問題的描述、解決方案的概述以及任何已知的風險或邊界。團隊需要理解提案的意圖，而不僅僅是字面意思。

## 研究階段

在開始編寫代碼之前，團隊通常會花一到三天的時間研究問題和可能的解決方案。這包括：
- 探索現有代碼
- 討論技術方法
- 考慮不同的設計方向

這個研究階段是重要的，但不應該持續太長時間。我們的目標是快速進入實際構建。

## 找到第一個要完成的部分

我們的方法不是從詳細的任務分解開始，而是找到一個"第一個要完成的部分"。這是一個垂直切片的功能，它：
- 觸及所有層（前端、後端、數據庫）
- 可以在真實環境中工作
- 解決了核心技術挑戰

例如，對於 PDF 導出功能，第一個要完成的部分可能是一個基本的導出按鈕，它生成一個空白的 PDF。這看起來很簡單，但它建立了從用戶界面到最終輸出的完整路徑。

## 從真實到虛擬

我們的方法是從真實開始，然後逐漸添加虛擬元素。這意味著：
- 首先構建一個可以在真實環境中工作的基本版本
- 然後添加更多功能和改進

這與從線框圖或模型開始的傳統方法相反。我們認為，只有當你有一個工作的基本版本時，你才能真正理解問題。

## 不要分解任務

我們不使用詳細的任務分解或故事點。相反，我們讓團隊自己決定如何實現提案。這給了他們自主權和創造性解決問題的空間。

當然，團隊成員會相互協調，但這是通過非正式的對話和共享的理解，而不是通過正式的任務分配。

## 設計與開發並行

在我們的團隊中，設計師和開發人員並行工作，而不是按順序工作。設計師不會先創建完整的設計，然後交給開發人員實現。相反，他們一起探索解決方案。

這種並行工作方式使團隊能夠更快地發現問題並調整方向。

## 具體到抽象

我們從具體的實現開始，然後根據需要進行抽象。這與先設計抽象然後填充細節的方法相反。

通過從具體開始，我們確保我們的抽象是基於真實需求的，而不是假設。

在下一章中，我們將討論如何將工作組織成可管理的範圍。

[上一章：第三部分：構建](./03-part3.html) | [下一章：整合](./03-9-map-the-scopes.html) 