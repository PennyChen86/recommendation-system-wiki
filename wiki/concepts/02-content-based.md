# Content-Based Filtering

**初步筆記：待完整 ingest 與原文逐段核對**

## 初步整理
內容式推薦利用項目間的特徵相似度，推薦和使用者先前喜歡的內容相似的項目。

## 教學例子
看過可愛動物影片後，系統推薦其他動物影片（簡化示意）。

## 資料來源
- [S04](../../raw/sources/S04.md)
- [S07](../../raw/sources/S07.md)

## 後續檢查
- 原始資料是否支持以上每個技術敘述？
- 需要補哪些章節／頁碼？
- 教學例子是否明確標為示意而非平台真實機制？

## 已核對證據卡（2026-11-15）

| 證據 | 來源 | 可用知識 |
|---|---|---|
| R04 | [G02 — Candidate generation overview](https://developers.google.com/machine-learning/recommendation/overview/candidate-generation) | 內容式推薦利用項目特徵相似性推薦接近使用者既有喜好的項目。 |
| R06 | [G02 — Embedding space; Similarity measures](https://developers.google.com/machine-learning/recommendation/overview/candidate-generation) | Embedding 將查詢與項目表示為向量；cosine、dot product、Euclidean distance 可用於衡量相似度或距離。 |
| R07 | [G02 — Comparing similarity measures](https://developers.google.com/machine-learning/recommendation/overview/candidate-generation) | 不同相似度量度可能產生不同排名；dot product 會受向量長度影響。 |
