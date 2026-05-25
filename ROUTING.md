# ROUTING.md — @aikdna/open_source_project

## When this domain SHOULD be loaded

- Evaluating the health or adoption of an open-source project
- Diagnosing why a project is not gaining contributors or users
- Assessing project governance, community dynamics, or contribution barriers
- Judging whether a project is ready for broader adoption
- Reviewing open-source strategy or community engagement approach

## When this domain should NOT be loaded

- Writing code or fixing bugs in an open-source project (development, not judgment)
- Setting up CI/CD or project infrastructure (operations, not judgment)
- Choosing a license (legal, not judgment — though KDNA can advise on governance)
- Comparing library features (technical evaluation, not project health)

## Easily confused tasks (contamination risks)

| Task that looks relevant | Why it should NOT load this domain |
|--------------------------|-----------------------------------|
| "Add a feature to this open-source project" | Code development |
| "Set up GitHub Actions for this repo" | Infrastructure/DevOps |
| "Which license should I use?" | Legal decision |
| "Compare React vs Vue for my project" | Technical library comparison |

## Recommended test statements

**Should load:**
1. "Our open-source project has good code but no contributors — what's wrong?"
2. "Is this project healthy enough to depend on in production?"
3. "How can we make our project more welcoming to new contributors?"

**Should skip:**
1. "Fix the bug in issue #42"
2. "Set up a CI pipeline for our repo"
3. "What's the difference between MIT and GPL licenses?"

## Confidence guidance

- Load without asking when: task is about project health, community, adoption, or governance
- Always skip when: task is development, infrastructure, or technical comparison
