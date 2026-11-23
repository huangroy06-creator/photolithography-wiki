# 半導體黃光微影製程入門｜LLM Wiki

> 對象：沒有半導體背景的大學生。知識庫為由 LLM 維護的跨文件 Markdown Wiki，並非只儲存供問答時查找的原始段落。

## 核心概念頁

- [01 製程總覽](concepts/01-process.md)：為何需要黃光、六大教學步驟、光阻到蝕刻的差異。
- [02 光阻與正負型](concepts/02-resist.md)：光阻感光後如何變化、顯影移除哪裡。
- [03 光學解析度](concepts/03-resolution.md)：瑞利式、波長、NA、k1、適用限制。
- [04 CD、Overlay、Throughput](concepts/04-measurement.md)：線寬、疊對、產能是不同問題。
- [05 常見誤解與測驗](concepts/05-misconceptions.md)：新手易錯觀念與解答。

## 來源頁：7 筆完成 ingest

- [S01 ASML 製造流程](sources/S01.md)
- [S02 ASML 曝光原理](sources/S02.md)
- [S03 ASML 瑞利式](sources/S03.md)
- [S04 EPFL 微影與光阻](sources/S04.md)
- [S05 Stanford 微影](sources/S05.md)
- [S06 Nikon 精度與產能](sources/S06.md)
- [S07 ASU 製程](sources/S07.md)

## Wiki 維運

- [Wiki 編輯規則](schema.md)
- [Wiki 索引、來源到簡報對應](coverage.md)
- [新增資料與檢查紀錄](log.md)
- [Graph 流程](../workflow/graph.md)

## 快速路徑

新資料進入 `raw/`（保留來源）→ 整理來源卡 → 更新一個或多個概念頁（含來源連結）→ 更新此 `index.md` → 執行檢查 → 產生或修改 `index.html`。
