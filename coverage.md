# 簡報頁面與 Wiki 資料來源對應

| HTML 頁碼 | 教學重點 | Wiki 概念頁 | 證據來源 |
|---|---|---|---|
| 01 | 簡報主題與學習目標 | index.md | S01, S02 |
| 02 | 為何需要微影 | 01-process | S01, S02 |
| 03 | 多層晶片與疊對 | 01-process, 04-measurement | S01, S06 |
| 04 | 六步驟總覽 | 01-process | S04, S07 |
| 05 | 正光阻 / 負光阻 | 02-resist | S04, S07 |
| 06 | 光罩與曝光 | 01-process | S02, S04 |
| 07 | 顯影與蝕刻 | 01-process, 02-resist | S05, S07 |
| 08 | CD ≈ k1 × λ / NA | 03-resolution | S03, S04 |
| 09 | CD、Overlay、Throughput | 04-measurement | S01, S06 |
| 10 | 新手常見誤解 | 05-misconceptions | S02, S03, S04, S07 |
| 11 | 三題教學檢核 | 05-misconceptions | S03, S04, S07 |
| 12 | 參考資料與總結 | index.md | S01–S07 |

**核對方法**：`index.html` 每頁設 `data-sources="..."`；`workflow/validate.py` 對照來源卡清單、頁數與 source ID，確認每頁有依據。概念與來源均可逐層追溯。
