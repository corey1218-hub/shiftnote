# 交接有序 ShiftNote

將零散的工程交接文字整理成可以搜尋、追蹤與匯出的紀錄。

這是生成式 AI 課程的 Vibe Coding 作品。靈感來自不同人員書寫交接本時，用詞與表達不一致的資料整理問題。網頁包含 12 筆虛構案例，沒有真實公司資料。

## 開啟

正式網站：[https://corey1218-hub.github.io/shiftnote/](https://corey1218-hub.github.io/shiftnote/)


直接開啟 index.html，不需要安裝套件。正式執行只有這一個檔案，CSS、JavaScript、圖示與範例均內嵌，沒有外部 CDN、API 或後端。

使用最新版的 Chrome、Edge、Firefox 或 Safari。瀏覽器對直接開啟本機檔案的資料儲存行為可能不同，正式驗收以 GitHub Pages 的 HTTPS 網址為準。

## 功能

- 新增、編輯、刪除、復原單筆紀錄。
- 關鍵字搜尋與分類、狀態、高優先度複合篩選。
- 依日期或優先度排序。
- 全部、待追蹤、高優先未結案、結案率與分類統計。
- 由固定中英文關鍵字產生分類提示；使用者確認後才套用。
- 匯出目前篩選結果為 CSV。
- localStorage 保存；JSON 全量備份與還原。
- 恢復範例、清空資料、錯誤與空結果提示。
- 桌面表格與窄螢幕卡片版面。

分類功能不是 AI 模型或設備診斷，不會自行決定故障原因、修復方式或設備放行。資料只在使用者自己的瀏覽器保存，沒有多人同步。

## 發布

本專案已使用 GitHub Pages 公開，來源為 main 分支的 /(root)。正式執行只需要 index.html，其他檔案為規格、修改紀錄與測試資料。

## 檔案

- index.html：完整網頁。
- SPEC.md：功能規格與驗收條件。
- CHANGELOG.md：本次實際製作與修正紀錄。
- TEST_REPORT.md：已完成與待完成的驗收。
- tests/core.test.cjs：核心資料邏輯檢查；網站執行不需要此檔。

執行資料邏輯檢查：node tests/core.test.cjs。
