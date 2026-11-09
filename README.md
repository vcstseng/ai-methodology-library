# AI Methodology Library｜AI 方法庫

整理近兩年因生成式 AI 與 agents 而出現或重新設計的工作方法，讓企業依手上的導入問題查找、比較與試行做法。

## 瀏覽網站

[開啟 GitHub Pages](https://vcstseng.github.io/ai-methodology-library/)

也可以直接用瀏覽器開啟本機的 [`site/index.html`](site/index.html)。網站使用靜態 HTML 與共用 CSS。

## 目錄結構

**Layer 1** 是六個並列的主題入口。治理貫穿全程，基線在試行前記錄。

**Layer 2** 按讀者帶來的問題組織，共 35 題。每題用一句話交代查閱範圍。

| 主題 | 問題數 |
| --- | ---: |
| [選題與可行性](site/topics/feasibility.html) | 6 |
| [流程與分工](site/topics/workflow.html) | 6 |
| [試行與交付](site/topics/pilot.html) | 5 |
| [驗證與衡量](site/topics/measurement.html) | 5 |
| [營運與演進](site/topics/operations.html) | 7 |
| [治理與管理](site/topics/governance.html) | 6 |

日常 token 用量監控放在營運與演進，按合格件數比較 token 效率放在驗證與衡量。

**Layer 3** 將收錄具體工作方法和管理手段。一個方法可以對應多個問題，內容維護一份。條目會說明做法、適用情境與限制，並區分作者主張、公開案例和實測結果。

## 專案檔案

- `site/index.html` — Layer 1 首頁。
- `site/topics/` — 六個 Layer 2 問題頁。
- `site/styles.css` — 首頁與主題頁的共用樣式。
- `content/` — 保留給方法與主題條目。
- `sources/` — 保留給原始來源與研究筆記。

推送 `site/` 的變更到 `main` 時，GitHub Actions 會重新部署網站。
