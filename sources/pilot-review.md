# 試行與交付｜五題來源審閱

查核日期：2026-11-09。先以工作問題跨產業找候選，再回原文核對範圍及可支持的說法。

| 問題 | 比較的候選來源與取捨 | 證據界線 |
| --- | --- | --- |
| 首輪試行範圍 | [澳洲 DTA 試行指引](https://www.digital.gov.au/policy/ai/pilot-ai-assurance-framework/guidance/step-5) 提供規劃欄位，[P&G 實地實驗](https://pubsonline.informs.org/doi/10.1287/orsc.2025.20702) 讓讀者看見如何選真實業務題目。亦看過 APQC 的 agent 管理指引，DTA 對試行範圍與期間更直接。 | 實驗規模及人員組成是研究設計，不能當成普遍建議。 |
| 基線與成功條件 | [客服實地研究](https://doi.org/10.1093/qje/qjae044) 把速度與結果一起記錄；[Magenta Book](https://www.gov.uk/government/publications/the-magenta-book/guidance-on-the-impact-evaluation-of-ai-interventions-html) 提供事前設定比較基準的評估框架，沿用既有條目。 | 客服研究的觀察項目可供參考。返工欄位和成功條件須按自己的流程訂定。 |
| 交付與審查 | [GitHub Agentic Workflows](https://github.github.com/gh-aw/reference/compliance-patterns/) 支持變更提案、檢查與合併紀錄；[NHS](https://digital.nhs.uk/data-and-information/information-governance/guidance/using-ai-enabled-ambient-scribing-products-in-health-and-care-settings/guidance-for-health-and-care-professionals) 和 [UCLH](https://www.uclh.nhs.uk/patients-and-visitors/patient-information-pages/supporting-patient-clinician-conversations-ai-assisted-documentation) 提供草稿到正式紀錄的另一產業案例。 | 兩者支持各自的交付機制，移用時要核對原流程的角色及退回機制。 |
| 停止與回退 | [NIST](https://airc.nist.gov/airmf-resources/playbook/manage/) 說明 AI 停用條件、責任和備援；[Google SRE](https://sre.google/workbook/canarying-releases/) 具體示範可控流量的技術回退。 | 不能把一般部署的回退當成已完成外部操作的撤銷機制。 |
| 員工說明與回報 | [澳洲 DTA 試行評估](https://www.digital.gov.au/initiatives/copilot-trial/microsoft-365-copilot-evaluation-report-full/employee-related-outcomes) 直接記錄員工對訓練的經驗；[Google SRE 事件指揮](https://sre.google/resources/practices-and-processes/incident-management-guide/) 用於需要立即處理的狀況，沿用既有條目。 | 志願參與和自述證據有其限制；調查回饋和事件通報要分開。 |

## 與既有題目的連結

- 基線連回 AI 影響評估，事故停用與通報分工沿用治理的原方法頁。
- 試行成果交付聚焦怎麼送進既有流程；驗收標準仍在「驗證與衡量」說明。
