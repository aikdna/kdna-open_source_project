# Open Source Project Benchmark Report

## Scope

This report covers `@aikdna/open_source_project` v0.7.5. The benchmark target
is diagnosing project adoption failure through value-entry clarity.

## Evidence

- Eval cases: `evals/eval-001.json` through `evals/eval-011.json`
- Known limitations: `docs/known-limitations.md`
- Quality badge target: `tested`

## Baselines

| Baseline | Purpose |
| --- | --- |
| No KDNA | Measures generic open-source advice. |
| Best Prompt | Checks whether prompting alone identifies value-entry failure. |
| Skill Only | Checks whether project-audit workflows over-focus on docs/features. |

## Expected Improvement

KDNA should identify whether a visitor can understand the problem, alternative,
and adoption reason within the first 30 seconds. It should avoid defaulting to
"write more docs" when the project value entrance is unclear.

## Known Failure Modes

- Over-emphasizing homepage messaging for deeply technical library audiences.
- Under-weighting ecosystem timing, maintainer reputation, or distribution.
- Mistaking intentionally narrow research projects for adoption-oriented tools.

## Status

This domain is suitable as a reference asset for developer-experience demos and
open-source project audits. It needs public raw outputs for promotion.
