# 推薦系統的限制

**初步筆記：待完整 ingest 與原文逐段核對**

## 初步整理
資料稀疏可能影響協同過濾；只優化點擊可能鼓勵聳動標題；多樣性不足則容易推薦重複內容。

## 教學例子
討論使用者是否會因為一直收到相似歌曲而失去探索新音樂的機會。

## 資料來源
- [S01](../../raw/sources/S01.md)
- [S05](../../raw/sources/S05.md)
- [S06](../../raw/sources/S06.md)
- [S07](../../raw/sources/S07.md)

## 後續檢查
- 原始資料是否支持以上每個技術敘述？
- 需要補哪些章節／頁碼？
- 教學例子是否明確標為示意而非平台真實機制？

## 已核對證據卡（2026-11-15）

| 證據 | 來源 | 可用知識 |
|---|---|---|
| R13 | [G04 — Choosing an objective function for scoring](https://developers.google.com/machine-learning/recommendation/dnn/scoring) | 只最大化點擊率可能促使系統推薦誘餌式內容；目標函數會影響實際結果。 |
| R14 | [G04 — Positional bias in scoring](https://developers.google.com/machine-learning/recommendation/dnn/scoring) | 位置偏差會影響使用者點擊；可以在設計評分時考慮位置獨立性。 |
| R16 | [G05 — Freshness; Diversity; Fairness](https://developers.google.com/machine-learning/recommendation/dnn/re-ranking) | 新鮮度、多樣性與公平性是推薦系統可能考慮的不同面向。 |
| R17 | [G05 — Diversity](https://developers.google.com/machine-learning/recommendation/dnn/re-ranking) | 若只推薦和當前內容極為相似的項目，可能造成單調體驗；可透過多來源候選、重新排序增加多樣性。 |

> 注意：「過濾泡泡」與「冷啟動」不應直接由這幾段教材推論為已經逐項驗證；正式簡報若要介紹，需額外查核綜述論文。
