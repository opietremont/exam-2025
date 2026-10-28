---
description: Verification rules — mandatory self-check before presenting any calculation or correction. Load for every exercise/correction task.
alwaysApply: true
---

# Verification Rule

- Before presenting any numeric or algebraic result, verify it by an **independent second method** — e.g. a decimal approximation computed alongside the exact fraction/symbolic derivation, or re-deriving from a different starting point. If the two disagree, resolve the discrepancy before answering; never present an unverified result.
- For any expression parsed from an external, non-generated source (a photo, a scanned PDF, a document the operator uploaded) — restate the parsed expression explicitly (parentheses, operator grouping, priorities) before computing. This is a distinct failure mode from an arithmetic mistake: misreading the source is often the actual error, not the calculation.
- Operator precedence is a common failure point: × and ÷ (and + and −) share priority and are evaluated **left to right** unless parentheses group them otherwise. When a source has ambiguous or tightly-packed parenthesization, check explicitly which operations are actually enclosed together before assuming a grouping.
- An unusually complex or "ugly" result (large uncommon denominator, no simplification) on a collège-level exercise is a signal to re-examine the parsing before finalizing — these exercises are designed to simplify cleanly. A surprisingly clean result (integer, simple fraction) is a corroborating signal, not proof on its own — still run the independent check.
- If any doubt about the source's parsing or an intermediate step remains after the check, say so explicitly to the operator rather than silently picking one interpretation and presenting it as certain.
- This applies to every correction task, including ad-hoc requests on external documents (e.g. a photographed DST) — not only to files generated under `daniel-3eme/`.
