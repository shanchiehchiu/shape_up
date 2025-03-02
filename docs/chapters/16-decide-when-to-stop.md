---
layout: default
title: 第十四章：範圍解決 | Shape Up 繁體中文翻譯
---

# 第十四章：範圍解決

在六週週期的後半段，團隊需要面對一個關鍵問題：我們何時該停止改進並開始交付？這是 Shape Up 方法中最具挑戰性的決策之一，需要權衡完美與實用性、理想與現實。本章探討如何在有限時間內做出明智的範圍決策。

## 時間緊迫的現實

當六週週期進入最後階段時，時間壓力變得越來越明顯。團隊可能面臨以下情況：

1. 一些範圍進展順利，而其他範圍落後
2. 出現了未預見的技術挑戰
3. 發現了新的用戶需求或邊緣情況
4. 某些功能比預期需要更多打磨

在這種情況下，團隊必須做出艱難但必要的決定：什麼是必須完成的，什麼可以簡化或推遲。

## 範圍解決的原則

在 Shape Up 中，我們使用以下原則來指導範圍決策：

### 1. 固定時間，可變範圍

最根本的原則是時間是固定的（六週週期），而範圍是可變的。這迫使我們在時間框架內優先考慮最重要的功能。

### 2. 核心優先，細節靈活

識別每個範圍的「核心」—— 沒有它功能就沒有意義的部分，以及「細節」—— 可以簡化或推遲的部分。保護核心，靈活處理細節。

### 3. 完成比完美更重要

我們優先考慮「完成」而非「完美」。一個簡化但功能完整的解決方案比一個未完成的完美解決方案更有價值。

## 優先級策略：The Hill Chart

在決定何時停止時，Hill Chart（山丘圖）是一個有價值的工具。它顯示了每個範圍在「向上爬坡」（弄清楚解決方案）和「下坡」（執行已知解決方案）階段的位置。

當時間有限時，團隊應該：

1. 專注於將「山頂」附近的範圍推到山下（完成執行）
2. 重新評估仍在爬坡的範圍 - 它們可能需要簡化或推遲
3. 確保至少核心功能的所有範圍都下山（完成）

## 範圍解決的策略

當面臨範圍壓力時，團隊可以採用以下策略：

### 1. 簡化而非刪除

不要完全刪除功能，而是尋找更簡單的實現方式。例如：
- 使用基本的表單而非複雜的交互界面
- 減少自動化，增加一些手動步驟
- 使用較少的視覺效果

### 2. 減少變體和選項

減少變體、選項和設置的數量。例如：
- 提供一種導出格式而非多種
- 減少定制選項
- 移除不常用的篩選條件

### 3. 減少細微的視覺改進

識別需要大量時間但對用戶體驗影響有限的視覺細節，並將其簡化。例如：
- 使用標準的動畫而非自定義動畫
- 減少複雜的佈局調整
- 使用系統默認控件而非高度自定義的控件

### 4. 技術簡化

考慮技術實現的簡化：
- 使用現有組件而非構建新組件
- 減少極端情況的處理
- 推遲性能優化（除非絕對必要）

## 何時堅持，何時簡化

並非所有情況都應該簡化範圍。某些情況下，值得投入額外時間：

### 堅持的情況

- 核心用戶流程 - 影響所有用戶的關鍵路徑
- 安全和數據完整性相關功能
- 關鍵的品牌體驗元素
- 使功能實用的必要元素

### 簡化的情況

- 極端邊緣情況（影響很少用戶的情況）
- 純粹的視覺裝飾
- 可在後續版本中改進的次要功能
- 使用頻率低的功能

## 範圍解決的溝通

範圍決策不是在真空中做出的。有效的溝通對於成功的範圍解決至關重要：

### 團隊內部溝通

- 定期討論範圍壓力和可能的解決方案
- 共同評估權衡取捨
- 確保團隊理解並支持決策

### 與利益相關者溝通

- 及早提出範圍挑戰
- 提供明確的權衡選項
- 解釋決策背後的邏輯
- 強調完成的價值

## 案例研究：簡化搜索功能

在 Basecamp，我們曾設計一個高級搜索功能，包含多種篩選器、保存的搜索以及複雜的結果顯示。

當我們意識到在六週內無法完成所有功能時，我們：
1. 識別了核心（快速準確的搜索結果）
2. 簡化了篩選界面，減少了選項
3. 推遲了保存搜索功能到下一個週期
4. 簡化了結果頁面的佈局

最終結果是一個功能更為簡單但完全可用的搜索功能，能夠解決用戶的核心問題。在後續週期中，我們逐步添加了更多高級功能。

## 結論

在軟件開發中，知道何時停止與知道如何構建同樣重要。優秀的產品開發不是關於追求完美，而是關於在時間限制內交付最大價值。

通過有意識地解決範圍問題，團隊可以避免無限期的項目、防止burnout、並建立穩定的交付節奏。這種方法確保我們不僅構建功能，還實際上將它們交付到用戶手中。

在下一章中，我們將討論如何將完成的工作交付給真實用戶，以及如何處理發布過程。

[上一章：第十五章：顯示進度](./15-show-progress.html) | [下一章：第四部分：延伸應用](./17-part4.html) 