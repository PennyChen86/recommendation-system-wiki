# HTML 簡報 ↔ Wiki 證據對照表

本表是 `slides/index.html` 的內容依據；來源以 `wiki/papers/Gxx.md` 的 R01–R17 證據為主。頁面例子屬於教學設計，不聲稱是 Spotify、Netflix 或 YouTube 內部實際演算法。

| 頁次 | 簡報主題 | Wiki 知識筆記 | 證據 ID | 檢查結果 |
|---|---|---|---|---|
| 1 | 封面與教學提問 | `01-basics.md` | 無技術斷言 | 通過 |
| 2 | 使用者訊號、回饋 | `01-basics.md`; `03-collaborative.md`; `05-pipeline.md` | R09、R12 | 通過 |
| 3 | Content-Based + 互動例子 | `02-content-based.md` | R04、R06 | 通過；互動例子標示為簡化 |
| 4 | Collaborative Filtering + 喜好矩陣 | `03-collaborative.md` | R05、R08、R10 | 通過；矩陣標示為示意 |
| 5 | 三階段架構 | `05-pipeline.md` | R01–R03、R11、R12、R15 | 通過；註明不是各平台唯一架構 |
| 6 | 點擊目標與多樣性 | `06-limitations.md` | R13、R16–R17 | 通過 |
| 7 | 互動小測驗 | `03-collaborative.md` | R05、R08 | 通過 |
| 8 | 複習與來源 | `01-basics.md`、`02-content-based.md`、`03-collaborative.md`、`05-pipeline.md` | R01、R04、R05 等 | 通過；5 筆原始連結 |

## 覆蓋率檢查與修改

最初規劃大綱包含「混合式推薦的詳細實作」以及「冷啟動／過濾泡泡」。但前一階段的 `wiki/concepts/04-hybrid.md`、`06-limitations.md` 已明確標示這些延伸主張在五篇網頁教材中未有充分直接證據。因此本版簡報**沒有把這些內容當成已驗證主張**；改以已有來源支持的評分目標與多樣性風險做第 6 頁。

這是**內容生成前的覆蓋率關卡**實際促成的範圍調整，比生成後再改整頁省去額外工作。
