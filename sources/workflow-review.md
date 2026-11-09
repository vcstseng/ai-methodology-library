# 流程與分工｜六題來源審閱

查核日期：2026-11-09。先按問題尋找候選，再查原始文件、實驗或工程紀錄。

| 問題 | 比較的候選來源與取捨 | 證據界線 |
| --- | --- | --- |
| 工作拆解與人機分工 | [AWS AI-DLC](https://aws.amazon.com/blogs/devops/ai-driven-development-life-cycle/) 提供階段與人工決策點，[Jagged Frontier 實驗](https://www.hbs.edu/ris/Publication%20Files/dell-acqua-et-al-2026-navigating-the-jagged-technological-frontier_5c589c8c-fbb5-458f-b285-c944746cd717.pdf) 說明為何應按任務驗證 AI 能力。 | 開發框架和顧問實驗的適用條件不同。 |
| AI 自主與人工接手 | [OpenAI](https://openai.com/business/guides-and-resources/a-practical-guide-to-building-ai-agents/) 有重試上限和高風險的觸發條件；沿用既有 GOV.UK 人工監督條目區分介入與一般運作。 | 沒有通用重試次數；核准範圍由組織決定。 |
| 任務與交付規格 | [Spec Kit](https://github.github.com/spec-kit/quickstart) 貫穿規格到實作檢查，[pstack 原則](https://github.com/cursor/plugins/blob/main/pstack/skills/principle-sequence-verifiable-units/SKILL.md) 補逐段驗收。 | 不把 pstack 的一項原則當成 Spec Kit 式的完整規格流程。 |
| AI 角色、技能與工具 | [gstack](https://github.com/garrytan/gstack) 提供具名角色和技能；[Anthropic 工具設計](https://www.anthropic.com/research/writing-tools-for-agents) 提供按任務選工具及測試的做法。 | 角色可能只是工作指令，不代表獨立 agent 或操作授權。 |
| 知識維護與寫回 | [KCS v6](https://library.serviceinnovation.org/KCS/KCS_v6/KCS_v6_Practices_Guide/020) 處理內容更新和重用，[AWS](https://d1.awsstatic.com/builderslibrary/pdfs/making-retries-safe-with-idempotent-apis-malcolm-featonby.pdf) 處理重試時避免重複寫入。 | 兩者是較早的管理與整合做法，借用到 AI 是編輯判斷。 |
| 多 agent 協作 | [Azure](https://learn.microsoft.com/en-us/azure/architecture/ai-ml/guide/ai-agent-design-patterns) 用於選模式，[Google ADK](https://adk.dev/workflows/patterns/) 作為配套；[Anthropic 研究系統](https://www.anthropic.com/research/multi-agent-research-system) 提供具體的委派和交付物實作。 | 架構指引和供應商實作不等於所有工作都受益於多 agent。 |

## 與既有題目的連結

- 人工接手題沿用既有人工監督條目，並連到治理的資料與操作授權。
- 任務規格題連到「驗證與衡量」的成果驗收。這樣可分別查閱任務交付前如何說清楚，以及交付後如何驗證。
