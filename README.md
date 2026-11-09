# AI Methodology Library｜AI 方法庫

整理近兩年因生成式 AI 與 agents 而出現或重新設計的工作方法，讓企業依手上的導入問題查找、比較與試行做法。

## 瀏覽網站

[開啟 GitHub Pages](https://vcstseng.github.io/ai-methodology-library/)

也可以直接用瀏覽器開啟本機的 [`site/index.html`](site/index.html)。網站使用靜態 HTML 與共用 CSS。

## 目錄結構

六個主題下的 35 個問題都可以查到相關做法。全站共有 55 個方法條目，每個條目附來源與證據說明。

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

日常 token 用量監控放在營運與演進，按合格件數比較 token 效率放在驗證與衡量。 [Token 效率題](site/questions/cost-per-accepted-outcome.html)說明如何用同一批案例和驗收標準比較不同做法。

**Layer 3** 收錄可追溯的工作方法。問題頁說明什麼情境適合參考、做法涵蓋哪一部分。同一套方法只維護一篇，可由多個問題連入。 共用方法頁會列出所有適用的問題，可直接回到原先查閱的題目。

**Layer 4** 是方法頁內的來源與證據，標明原始指引、實作紀錄或供應商發布的採用案例，以及各來源能支持的說法。

## 問題與來源審閱

### 營運與演進

- [試行成功後，怎麼變成團隊的日常工作？](site/questions/pilot-to-daily-work.html)
- [誰負責維護、培訓和交接？關鍵人員離開時，誰能接手？](site/questions/ownership-and-handover.html)
- [員工不願意用，或用了以後不再檢查，該怎麼處理？](site/questions/adoption-and-human-review.html)
- [怎麼監控日常 token 用量和費用，發現異常時誰來查？](site/questions/token-usage-monitoring.html)
- [什麼時候該擴大使用？換一個團隊前要重驗哪些條件？](site/questions/phased-expansion.html)
- [AI 能力或工具變了，什麼時候該重新設計流程？](site/questions/workflow-redesign.html)
- [供應商漲價、停服或改條款時，怎麼切換工具或退回原本的做法？](site/questions/supplier-exit-and-fallback.html)

[營運與演進來源審閱](sources/operations-review.md)記錄候選做法、收錄理由與證據界線。

### 治理與管理

- [AI 可以讀取哪些資料、執行哪些操作？誰能授權？](site/questions/ai-access-and-authorization.html)
- [哪些 AI 操作或決定要先由人核准？誰能核准政策例外？](site/questions/human-approval-and-exceptions.html)
- [員工已經在用未經核准的 AI 工具，該怎麼納入管理？](site/questions/shadow-ai-governance.html)
- [使用客戶資料或 AI 產出時，要確認哪些法規、合約和智慧財產要求？](site/questions/customer-data-and-ai-outputs.html)
- [出事時誰能暫停、復原和通知受影響的人？誰對外負責？](site/questions/ai-incident-response.html)
- [哪些變化會觸發重新審查權限、風險和管理規則？](site/questions/ai-change-reassessment.html)

[治理與管理來源審閱](sources/governance-review.md)記錄收錄理由、證據界線和既有條目的修訂。

### 驗證與衡量

- [怎麼驗收 AI 的成果？什麼算通過？](site/questions/acceptance-criteria.html)
- [怎麼抓出看起來正確、其實有錯的結果？](site/questions/detect-plausible-errors.html)
- [誰來驗收？什麼時候需要獨立覆核？](site/questions/independent-acceptance-review.html)
- [和原本的做法相比，品質、工時和返工有沒有改善？](site/questions/compare-ai-workflow-impact.html)
- [每件通過驗收的工作用了多少 token、花了多少錢？換一種做法會更有效率嗎？](site/questions/cost-per-accepted-outcome.html)

[驗證與衡量來源審閱](sources/measurement-review.md)記錄候選做法、收錄理由與證據界線。

### 試行與交付

- [第一輪要試哪一段工作？範圍多大才看得出效果？](site/questions/pilot-scope.html)
- [試行前要記錄哪些基線、訂哪些成功條件？](site/questions/pilot-baseline-and-success.html)
- [試行成果怎麼交付、審查並接回原有流程？](site/questions/pilot-delivery-and-review.html)
- [遇到什麼情況要停止試行，退回原本的做法？](site/questions/pilot-stop-and-rollback.html)
- [怎麼讓參與試行的員工知道要做什麼、去哪裡回報問題？](site/questions/pilot-staff-briefing-and-feedback.html)

[試行與交付來源審閱](sources/pilot-review.md)記錄候選做法、收錄理由與證據界線。

### 流程與分工

- [這份工作怎麼拆？人和 AI 各負責哪一段？](site/questions/task-decomposition.html)
- [哪些工作可以讓 AI 自己完成？何時要交回人處理？](site/questions/autonomy-and-human-handoff.html)
- [怎麼把任務、限制和交付要求說清楚？](site/questions/task-specification.html)
- [需要哪些 AI 角色、技能和工具？](site/questions/agent-roles-skills-and-tools.html)
- [怎麼整理工作知識，讓 AI 用到正確的資料，並把結果送回既有系統？](site/questions/knowledge-and-system-writeback.html)
- [多個 AI 一起做事時，怎麼分工、共享資訊和交接？](site/questions/multi-agent-coordination.html)

[流程與分工來源審閱](sources/workflow-review.md)記錄候選做法、收錄理由與證據界線。

### 選題與可行性

- [哪些工作值得先用 AI？](site/questions/ai-use-case-prioritization.html)
- [現有的資料和知識夠用嗎？](site/questions/data-and-knowledge-readiness.html)
- [既有系統接得上嗎？有哪些技術限制？](site/questions/legacy-integration-feasibility.html)
- [導入、人工審查和長期維護，總共要花多少錢？](site/questions/estimate-ai-total-cost.html)
- [該買現成產品、組合既有工具，還是自己開發？](site/questions/build-buy-or-compose.html)
- [誰出資、誰對成果負責？相關團隊有共識嗎？](site/questions/funding-and-ownership.html)

[選題與可行性來源審閱](sources/feasibility-review.md)記錄候選做法、收錄理由與證據界線。

## 專案檔案

- `site/index.html` — Layer 1 首頁。
- `site/topics/` — 六個 Layer 2 問題頁。
- `site/questions/` — 問題頁與相關方法的入口。
- `site/methods/` — 方法條目與來源紀錄。
- `site/styles.css` — 網站的共用樣式。
- `content/` — 保留給方法與主題條目。
- `sources/` — 保留給原始來源與研究筆記。

推送 `site/` 的變更到 `main` 時，GitHub Actions 會重新部署網站。
