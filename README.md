# 數位易經 · 三數起卦（早期版）

三數起卦的易經占卜，支援事業、健康、愛情、財運、投資、購物、官司、購屋八大類。

**線上使用**：https://kftseng2oo1.github.io/ichen2/

## 主要功能
- 選擇占卜事項：事業、健康、愛情、財運、投資、購物、官司、購屋
- 輸入三個數字（0–9）：第一數定上卦、後兩數相加定下卦、三數相加定動爻
- 顯示本卦與變卦（動爻會發光標示）、動爻名稱、吉凶與建議
- 支援安裝到主畫面、離線使用

## 備註
- 2026-10 修復：原 `index.html` 被截斷且混入一行 Markdown 標記，App 無法使用；同時修正了爻序錯誤（見 PR #2）。
- 解讀資料只有每個類別一組通用文字，內容更完整的版本是 [v3](https://github.com/kftseng2oo1/v3) 和 [gold](https://github.com/kftseng2oo1/gold)。

## 技術與依賴
- 單檔 HTML PWA（`index.html`），`manifest.json` + `sw.js` 提供安裝與離線快取；純前端、無外部連線

## 相關 repo
- 易經同系列：[gold](https://github.com/kftseng2oo1/gold)（完整版）、[v3](https://github.com/kftseng2oo1/v3)（優化版＋紀錄）、[digital-ichen](https://github.com/kftseng2oo1/digital-ichen)、[DE2.3](https://github.com/kftseng2oo1/DE2.3)、[v2.2](https://github.com/kftseng2oo1/v2.2)、[ichen2](https://github.com/kftseng2oo1/ichen2)、[ichen3](https://github.com/kftseng2oo1/ichen3)
