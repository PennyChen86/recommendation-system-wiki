# Collaborative Filtering

**初步筆記：待完整 ingest 與原文逐段核對**

## 初步整理
協同過濾利用使用者—項目的偏好或互動模式推測未知喜好，包含記憶式、模型式等不同方法。

## 教學例子
喜歡相似歌曲的兩位聽眾可能互相得到新歌推薦（簡化示意）。

## 資料來源
- [S01](../../raw/sources/S01.md)
- [S04](../../raw/sources/S04.md)

## 後續檢查
- 原始資料是否支持以上每個技術敘述？
- 需要補哪些章節／頁碼？
- 教學例子是否明確標為示意而非平台真實機制？

## 已核對證據卡（2026-11-15）

| 證據 | 來源 | 可用知識 |
|---|---|---|
| R05 | [G02 — Candidate generation overview](https://developers.google.com/machine-learning/recommendation/overview/candidate-generation) | 協同過濾綜合使用者與項目間的互動模式，可找到未必內容相似的項目。 |
| R08 | [G03 — Movie recommendation example](https://developers.google.com/machine-learning/recommendation/collaborative/basics) | 協同過濾可從偏好矩陣學習使用者與項目的關係，並生成預測。 |
| R09 | [G03 — Movie recommendation example](https://developers.google.com/machine-learning/recommendation/collaborative/basics) | 顯式回饋例如評分，隱式回饋例如觀看行為；觀看不等於一定喜歡。 |
| R10 | [G03 — 1D embedding; 2D embedding](https://developers.google.com/machine-learning/recommendation/collaborative/basics) | 使用者與項目嵌入向量可被放在同一個表示空間，並透過訓練學習。 |
