> 🧬 [aikdna.com](https://aikdna.com) — Official website

# @aikdna/open_source_project

[![KDNA Spec](https://img.shields.io/badge/KDNA-v1.0--rc-4c1)](https://github.com/aikdna/KDNA)

**Open-source project judgment** — diagnose why a project is not gaining adoption. The root cause is usually value-entry clarity, not documentation or feature gaps.

## What this KDNA changes

**Before loading this KDNA, an agent tends to:**
- Suggest improving documentation, adding features, or better marketing
- Treat adoption failure as a feature gap

**After loading this KDNA, an agent will judge:**
- Can a visitor determine in 30 seconds what problem this solves?
- Why is this project better than alternatives?
- Is the value-entry path clear and immediate?
- Is time-to-first-value measured and minimized?

## This KDNA is for

- Evaluating open-source project adoption
- Reviewing a repo for improvement
- Diagnosing why a project is not being used

## This KDNA is not for

- Code quality analysis
- CI/CD setup or maintainer handbooks
- Funding strategy or growth marketing
- Implementation correctness evaluation

## Core judgment

Adoption failure is a value-entry problem: visitors cannot determine in 30 seconds what problem this solves and why it is better.

## Self-checks

- Can a first-time visitor understand the value in 30 seconds?
- Is the comparison to alternatives honest and clear?
- Is time-to-first-value measurable?
- Is the project solving a real problem or just showcasing technology?

## Install

```bash
kdna install @aikdna/open_source_project
kdna dev validate .
```

## Files

- `KDNA_Core.json` — Axioms, ontology, frameworks, causal structure, stances
- `KDNA_Patterns.json` — Terminology, banned terms, misunderstandings, self-checks
- `KDNA_Scenarios.json` — Scenario signals that shift strategy
- `KDNA_Cases.json` — Concrete cases showing judgment structure
- `KDNA_Reasoning.json` — Reasoning chains: conclusion → logic → action
- `KDNA_Evolution.json` — Capability stages, measurable indicators, growth paths
- `evals/` — Evaluation cases (quality: untested)
- `kdna.json` — Domain manifest

## License

CC BY 4.0
