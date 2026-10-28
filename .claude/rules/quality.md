---
description: Quality rules — pedagogical standards for exercises and corrections. Load when generating or reviewing exercises.
globs: ["daniel-3eme/**/*.md"]
alwaysApply: false
---

# Quality Rule

## Énoncé (enonces/<theme>/NN-<theme>.md)
- Questions numérotées, données fournies explicitement.
- Exactement 10 questions par feuille d'exercice.
- QCM interdit. Types autorisés : calcul, vrai/faux justifié, problème contextualisé, phrase à compléter, démonstration, comparaison.
- No answers, no hints — énoncé only.

## Corrigé (corriges/<theme>/NN-<theme>-corrige.md)
- Every formula must come from the active skill — no improvisation.
- Full method required: data → formula → substitution → result with unit.
- Chemical equations must be verified as balanced before inclusion.
- Justify every answer, including true/false.
- Every result independently re-verified before being written down (see `.claude/rules/verification.md`) — no exceptions, including ad hoc corrections outside `daniel-3eme/`.

## General
- Numerical data must be provided in the énoncé — never ask Daniel to look it up.
- Both files are always created together.
- Simple diagrams (circuits, ray optics): ASCII is acceptable.
- Complex diagrams (curves, graphs, multi-series plots): use SVG, saved in `enonces/<theme>/figures/`, referenced by the exercise via a relative Markdown image link (`figures/NN-figK.svg`).
- Estimate the working time of every new sheet (realistic for Daniel, no calculator, full write-up) and record it in the index.
