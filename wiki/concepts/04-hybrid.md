# Hybrid Recommendation

**初步筆記：待完整 ingest 與原文逐段核對**

## 初步整理
混合式推薦可整合協同過濾與內容式推薦等訊號，以克服單一方法的部分限制。

## 教學例子
同時考慮歌的類型與其他聽眾的偏好（示意）。

## 資料來源
- [S01](../../raw/sources/S01.md)
- [S07](../../raw/sources/S07.md)

## 後續檢查
- 原始資料是否支持以上每個技術敘述？
- 需要補哪些章節／頁碼？
- 教學例子是否明確標為示意而非平台真實機制？

## 已核對證據卡（2026-11-15）

| 證據 | 來源 | 可用知識 |
|---|---|---|
| R04 | [G02 — Candidate generation overview](https://developers.google.com/machine-learning/recommendation/overview/candidate-generation) | 內容式推薦利用項目特徵相似性推薦接近使用者既有喜好的項目。 |
| R05 | [G02 — Candidate generation overview](https://developers.google.com/machine-learning/recommendation/overview/candidate-generation) | 協同過濾綜合使用者與項目間的互動模式，可找到未必內容相似的項目。 |
| R11 | [G04 — Why not let the candidate generator score?](https://developers.google.com/machine-learning/recommendation/dnn/scoring) | 不同候選生成器產生的分數不一定可直接比較，因此可以用共同評分模型排序。 |

> 注意：這五份官方教材分別介紹多種推薦方法及多來源候選，不足以單獨證明特定混合式模型的所有實作細節；本章深入內容仍待原始 Survey 補強。
