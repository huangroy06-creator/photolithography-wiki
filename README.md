# 半導體黃光微影製程入門｜LLM Wiki + HTML 教學簡報

本專案完成課堂要求的 **LLM Wiki、7 篇公開資料 ingest、12 頁教學 HTML 簡報、loop/graph、實作檢查紀錄與反思**。

## 立即使用

1. 解壓縮後雙擊 `index.html`（Chrome/Edge/Firefox）即可播放簡報。
2. 鍵盤 `←`、`→`、空白鍵翻頁；可滑鼠按左右箭頭，手機可左右滑動。
3. 互動頁：正負光阻比較、瑞利式參數調整、小測驗。
4. 閱讀 `wiki/index.md` 查看 LLM Wiki 的概念與跨來源整合。
5. `workflow/graph.md` 查看流程；`workflow/check_log.md` 及 `workflow/reflection.md` 做為繳交文字參考。

## 目錄

```text
index.html                  教學 HTML 簡報（單一檔案，無外部依賴）
raw/S01.md … S07.md         每篇來源的唯讀摘記卡（非原文全文）
raw/manifest.json           來源登記、連結與 ID
wiki/index.md               Wiki 索引
wiki/concepts/             五個跨來源知識頁
wiki/sources/              七個來源頁
wiki/schema.md              LLM wiki 維護規則
wiki/log.md                 ingest 與更新日誌
wiki/coverage.md            簡報與來源對照
workflow/graph.md           Loop/Graph 文字與 Mermaid
workflow/discussion.md      設計規格的先討論紀錄
workflow/check_log.md       測試紀錄
workflow/reflection.md      本次反思
workflow/validate.py        自動檢查程式
```

## 發布 HTML 連結（GitHub Pages）

1. 新建 GitHub **public** repository，例如 `lithography-lesson`。
2. 上傳根目錄的 `index.html`，也可把其他檔案一併上傳。
3. 到 **Settings → Pages → Build and deployment → Deploy from a branch**，選 `main`、`/(root)`、Save。
4. 部署完成後取得形如 `https://你的帳號.github.io/lithography-lesson/` 的實際網址，填入繳交內容。不應把範例網址當成已存在的連結。

**來源註明**：技術事實改寫自 ASML、EPFL、Stanford、Nikon、ASU 的公開網頁；每份均存有原始連結。raw 卡不是未授權的完整網站複製。若作業老師要求上傳完整原始文檔，需另外依原網站授權自行下載並加以來源註記。
