# 驗證與衡量｜五題來源審閱

查核日期：2026-11-09。收錄理由與跨情境移用均屬編輯判斷。

| 問題 | 比較的候選來源與取捨 | 證據界線 |
| --- | --- | --- |
| 驗收與通過條件 | [Anthropic](https://www.anthropic.com/research/demystifying-evals-for-ai-agents) 具體分開 agent 說了什麼、實際達成什麼；[NIST Measure 2.3](https://airc.nist.gov/airmf-resources/playbook/measure/) 補足代表性部署條件。兩者沿用既有條目。 | 案例支持具體測法；通過條件仍由使用者與負責團隊按任務決定。 |
| 查證與重算 | [NIST 生成式 AI Profile](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.600-1.pdf) 直接要求來源與引用查核；[AQuA Book](https://www.gov.uk/guidance/the-aqua-book) 補分析覆核，另引[歷史版操作示例](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/416478/aqua_book_final_web.pdf)支持重算。 | 查引文與重算是不同控制。兩者都無法保證沒有未測到的錯誤。 |
| 驗收責任與獨立覆核 | [AQuA Book](https://www.gov.uk/guidance/the-aqua-book) 說明分析成果的覆核分工；[NIST Measure 1.3](https://airc.nist.gov/airmf-resources/airmf/5-sec-core/) 說明系統層級的定期獨立評估。既有人工監督條目偏運行中介入，因此未列為本題主方法。 | 兩種做法的評估對象不同，不推定每件成果都必須由外部人員簽核。 |
| 比較導入成效 | [Magenta Book AI 影響評估](https://www.gov.uk/government/publications/the-magenta-book/guidance-on-the-impact-evaluation-of-ai-interventions-html) 提供比較設計；[METR 研究](https://metr.org/blog/2025-07-10-early-2025-ai-experienced-os-dev-study/) 是隨機分派實例，並保留[作者後續對設計的檢討](https://metr.org/blog/2026-02-24-uplift-update/)。 | 案例結果限當時的開源開發工作。沒有可比較條件的前後差異只能說明觀察到的變化。 |
| 每件合格成果的用量和費用 | [FinOps for AI](https://www.finops.org/wg/finops-for-ai-overview/) 直接提供成功結果成本公式；[OpenTelemetry](https://opentelemetry.io/blog/2026/genai-observability/) 提供調用層的資料。既有異常告警方法回答誰處理突增，留在營運。 | Token 比值為本站應用。計算須交代成本範圍、合格標準和紀錄覆蓋率。 |

## 與既有題目的連結

- 能力／回歸測試與部署情境重驗沿用原方法頁，並補上成果驗收的入口。
- 調用追蹤沿用原方法頁。日常監控與每件合格成果的比較可互相切換。
