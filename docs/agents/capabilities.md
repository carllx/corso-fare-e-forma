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
