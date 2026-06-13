---
description: Review scientific manuscript writing quality — five-pass audit (clutter, voice, structure, keywords, numbers) based on Writing in the Sciences methodology
model: sonnet
---

Load and apply the `manuscript-writing-review` skill from `SKILL.md`.

Perform a writing quality review of the manuscript text provided by the user. Default to **full-review** mode (all five audit passes) unless the user specifies a different mode:

- `full-review` — all five passes on the entire document
- `section-review` — all five passes on a single section
- `targeted` — only the pass(es) the user requests (e.g. "fix passive voice")
- `interactive` — paragraph-by-paragraph with before/after examples

Skill reference: `SKILL.md` (manuscript-writing-review).
