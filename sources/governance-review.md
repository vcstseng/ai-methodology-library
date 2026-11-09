# 治理與管理｜六題來源審閱

查核日期：2026-11-09。收錄理由及跨情境移用均屬編輯判斷。

| 問題 | 比較的候選來源與取捨 | 證據界線 |
| --- | --- | --- |
| 資料與操作授權 | [OWASP](https://genai.owasp.org/llmrisk/llm062025-excessive-agency/) 有細到下游授權的控制方式；[澳洲共同指引](https://www.cyber.gov.au/publication/careful-adoption-of-agentic-ai-services) 補可用工具清單。角色配置重用既有 Microsoft CoE 條目。 | 最小權限與授權權責需要一起設計；技術指引無法決定某家公司的授權人。 |
| 人工核准與例外 | [OWASP](https://genai.owasp.org/llmrisk/llm062025-excessive-agency/) 與既有 GOV.UK 人工監督條目支持高影響操作的核准；[Wharton](https://support.wharton.upenn.edu/help/exception-standard) 比 [Stanford](https://uit.stanford.edu/security/exception) 更明列風險分級與續期路徑，作為主實例。 | 兩家學校是資安例外制度的實例，不能當成通用期限或 AI 法規。 |
| 影子 AI | [Microsoft Purview](https://learn.microsoft.com/en-us/purview/deploymentmodels/depmod-data-leak-shadow-ai-step1) 回答應用盤點和敏感資料訊號；[NCSC](https://www.ncsc.gov.uk/guidance/shadow-it) 回答工具未滿足實際工作的問題。[NIST Govern 1.6](https://airc.nist.gov/airmf-resources/playbook/govern/) 是一般盤點框架，沒有同等細節說明怎麼發現已在使用的外部工具。 | 供應商文件可解釋工具的做法，不能推定偵測涵蓋所有使用。 |
| 客戶資料、合約與產出 | [ICO 合約指引](https://ico.org.uk/for-organisations/advice-and-services/audits/data-protection-audit-framework/toolkits/artificial-intelligence/contracts-and-third-parties/) 用於資料、角色和第三方合約；[美國著作權局報告](https://www.copyright.gov/ai/Copyright-and-Artificial-Intelligence-Part-2-Copyrightability-Report.pdf) 用於產出的人類創作與可保護性。兩者分開收錄。 | 各有地區限制。未判定任何企業的特定資料可否交給供應商，也未判定產出的契約歸屬。 |
| 事件應變 | [NIST Manage](https://airc.nist.gov/airmf-resources/playbook/manage/) 直接談 AI 停用與恢復；[Google SRE](https://sre.google/resources/practices-and-processes/incident-management-guide/) 補事件指揮、技術與溝通分工。既有英國備援條目偏供應商失效，留在營運問題。 | 分工指引未決定特定事件的法定通報義務或責任歸屬。 |
| 變更後重審 | [GOV.UK Toolkit](https://www.gov.uk/government/publications/ai-risk-management-toolkit/ai-risk-management-toolkit-guidance) 明列資料、模型及情境變動；[NIST Govern](https://airc.nist.gov/airmf-resources/playbook/govern/) 補回顧責任和頻率。沿用既有 Anthropic 測試條目說明如何重驗行為。 | 重驗結果不能自行替代授權或風險接受決定。 |

## 題目與前一批的修訂

- 人工核准題明列「操作或決定」與「政策例外」，讓讀者分清每次操作的核准和暫時偏離既有控制。
- 「營運與演進」的流程重設頁補上治理重審入口。既有角色分工、人工監督與回歸測試條目可由治理題目連入，也加上對應的返回路徑。
