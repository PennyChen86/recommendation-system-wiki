# Candidate Generation → Scoring → Re-ranking

**初步筆記：待完整 ingest 與原文逐段核對**

## 初步整理
候選生成先縮小項目集合；評分比較候選項目；重新排序可考慮多樣性、新鮮度與公平性。YouTube 2016 論文不等於當前所有平台的內部演算法。

## 教學例子
圖示從 1000 個候選影片逐步選出推薦清單（數字僅供示意）。

## 資料來源
- [S02](../../raw/sources/S02.md)
- [S03](../../raw/sources/S03.md)
- [S05](../../raw/sources/S05.md)
- [S06](../../raw/sources/S06.md)

## 後續檢查
- 原始資料是否支持以上每個技術敘述？
- 需要補哪些章節／頁碼？
- 教學例子是否明確標為示意而非平台真實機制？

## 已核對證據卡（2026-11-15）

| 證據 | 來源 | 可用知識 |
|---|---|---|
| R01 | [G01 — Recommendation systems overview](https://developers.google.com/machine-learning/recommendation/overview/types) | 常見推薦流程包含候選生成、評分、重新排序三個階段。 |
| R02 | [G01 — Candidate generation](https://developers.google.com/machine-learning/recommendation/overview/types) | 候選生成將大量項目縮小成較小候選集，以便後續細緻比較。 |
| R03 | [G01 — Scoring; Re-ranking](https://developers.google.com/machine-learning/recommendation/overview/types) | 評分階段對候選集進行排序；重新排序再考慮多樣性、新鮮度、公平性等限制。 |
| R11 | [G04 — Why not let the candidate generator score?](https://developers.google.com/machine-learning/recommendation/dnn/scoring) | 不同候選生成器產生的分數不一定可直接比較，因此可以用共同評分模型排序。 |
| R12 | [G04 — Scoring](https://developers.google.com/machine-learning/recommendation/dnn/scoring) | 評分模型可以使用使用者觀看歷史等查詢特徵，以及影片標題、標籤等項目特徵。 |
| R15 | [G05 — Re-ranking](https://developers.google.com/machine-learning/recommendation/dnn/re-ranking) | 重新排序可透過過濾或調整分數處理額外限制，例如排除誘餌標題項目。 |
