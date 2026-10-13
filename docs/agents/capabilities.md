# Project Capabilities

## course-notebook
- Kind: external-knowledge
- Provider: NotebookLM
- Purpose: 查询本课程已有书目、理论、案例、教研笔记与研究素材
- Scope: 《造物与创格》课程研究与课程设计
- Known host: IDE
- Access hint: /notebooklm
- Notebook: 造物与创格
- Locator: c7f9c10a-10db-454d-ab7a-ba307cb4612d

### Boundary
- Declaration does not guarantee runtime availability.
- Locator does not imply Browser readability.
- NotebookLM is retrieval / synthesis support, not Project Authority.
- Auth/session secrets remain host-local and must not enter Git or relay payloads.

### Routing Trigger
When a curriculum-design work unit (especially a Stage Contract) depends materially on existing:
- textbooks / source books
- theoretical interpretations
- artist / case-study material
- prior teaching notes
- prior NotebookLM synthesis

and those questions are not already sufficiently settled by official institutional sources or current Project Authority, the Browser/Agent should explicitly evaluate whether course-notebook is load-bearing.

If load-bearing:
- route the narrowest necessary Knowledge / Fact Probe to the declared Known host;
- for the current user-invoked access path, the user must explicitly invoke /notebooklm in the IDE host;
- do not perform broad Notebook scans by default.

Do NOT invoke course-notebook mechanically when:
- the task is only checking official schedules / institutional rules;
- current Project Authority already answers the question sufficiently;
- external knowledge would not materially affect the decision.

Evidence semantics:
- NotebookLM results remain Reported with provenance;
- NotebookLM is not Project Authority;
- adopted conclusions must be persisted back into the appropriate repo artifact before becoming shared project state.

## course-mindmap
- Kind: visual-knowledge / collaborative-mindmap
- Provider: Whimsical
- Purpose: 四阶段课程知识结构、22 个候选知识主题、艺术家与作品案例的可视化协作和教学对照
- Known host: ChatGPT Browser（已通过 Whimsical 连接验证读写能力）
- Locator: https://whimsical.com/MPwgA6RTzw5B1YGtADuhdd
- Authority: 非规范性协作视图；GitHub 课程文档、研究索引与已确认教师决定仍为正式依据

### Usage Rules & Boundary
1. 当任务涉及课程知识点、艺术家案例、四阶段结构或教学衔接时，Agent 按需读取最新思维导图，与 GitHub 当前权威内容对照。
2. 聚焦教师的新增、删除、修改和节点调整，分析其教学意图及跨阶段影响。
3. 仅当有明确作者证据时，才将修改认定为教师操作；不能识别时标记 `UNATTRIBUTED`。
4. 当前 `Primary` 与 `carllllllllx` 连接实际对应同一 Whimsical 身份，不得将其误认为两个独立的修改者。
5. 导图变化不自动成为教师确认的正式决策。实质性课程决定须经教师确认后回写现有 GitHub 权威文档。
6. 此声明只提供按需访问能力，不代表自动启用后台监控或定期同步。
