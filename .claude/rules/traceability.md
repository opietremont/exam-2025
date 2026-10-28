---
description: Traceability rules — file naming, headers, and index maintenance. Load when creating or listing exercise files.
globs: ["daniel-3eme/**/*.md", "daniel-3eme/index.md"]
alwaysApply: false
---

# Traceability Rule

- File naming convention (full rationale in `README.md` at repo root):
  - Énoncé : `daniel-3eme/<matiere>/enonces/<theme>/NN-<theme>.md`
  - Corrigé : `daniel-3eme/<matiere>/corriges/<theme>/NN-<theme>-corrige.md`
  - Figures : `daniel-3eme/<matiere>/enonces/<theme>/figures/NN-figK.svg`
  - Operator-supplied documents (scans, teacher sheets) : `daniel-3eme/<matiere>/sources/AAAA-MM-JJ-<description>.pdf`
  - `<theme>`: lowercase, no accents, hyphen-separated. `NN`: two digits, single counter per subject across all themes (next free number = highest in the index + 1).
  - A PDF export keeps the exact basename of its `.md`.
- Always create both files together — never one without the other.
- Each file must include a header with: subject, chapter, and date.
- Maintain `daniel-3eme/index.md` — one line per exercise, in the subject's table: number, theme, content, **estimated duration**, links to both files.
- Update the index immediately after creating a new exercise pair.
