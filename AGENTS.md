# Agent Guidelines for corso-fare-e-forma

## Agent skills

### Issue tracker

Tracked in GitHub Issues using the `gh` CLI. See `docs/agents/issue-tracker.md`.

### Triage labels

Canonical five-role triage vocabulary. See `docs/agents/triage-labels.md`.

### Domain docs

Single-context layout (`CONTEXT.md` + `docs/adr/`). See `docs/agents/domain.md`.

### Course preparation

- For course-preparation tasks, start from the current applicable official teaching requirements, `docs/current-course-baseline.md`, and the latest frontier in GitHub Issue #11. Verify the actual department, class and teaching scope; do not reuse outdated class assumptions.
- Follow the teacher-confirmed A–F research-driven preparation method recorded in Issue #11: source research, teacher knowledge bridge, collaborative judgment, classroom translation, observable evidence and decision backwrite.
- Verify at runtime whether `docs/teaching-map.md` (e.g. from PR #12 or successor updates) has merged into `main`. Do not treat proposed or unmerged content as effective course authority.
- Research material and artist cases are non-normative until individually verified and selected. Locate the research index through Issue #11 and its reviewed Git refs; do not assume the file exists on `main`.
- Route external knowledge, mind-map and visual-note work through the available project capabilities and the actual runtime host. External views do not supersede official requirements or teacher-confirmed decisions.
- Treat internal meeting records, transcripts, draft teaching plans and their Git history as restricted sources. Do not publish them to the public repository without explicit authorization.

### External capabilities

Project-declared capabilities. See `docs/agents/capabilities.md`.
