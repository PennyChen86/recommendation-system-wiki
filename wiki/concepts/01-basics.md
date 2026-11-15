# 推薦系統基本概念

**初步筆記：待完整 ingest 與原文逐段核對**

## 初步整理
推薦系統利用使用者和項目的資訊來決定推薦內容；Google 的常見架構分成候選生成、評分、重新排序三階段。

## 教學例子
從大量候選影片挑出少量可能感興趣的內容。

## 資料來源
- [S03](../../raw/sources/S03.md)
- [S07](../../raw/sources/S07.md)

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
| R09 | [G03 — Movie recommendation example](https://developers.google.com/machine-learning/recommendation/collaborative/basics) | 顯式回饋例如評分，隱式回饋例如觀看行為；觀看不等於一定喜歡。 |
