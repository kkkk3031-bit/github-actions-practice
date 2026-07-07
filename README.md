# GitHub Actions — certification practice

Hands-on workflows for the [GitHub Actions certification](https://examregistration.github.com/certification/actions),
covering the exam topics not exercised by my real projects. Each file is one
concept. Full study guide lives in my Obsidian vault (`Wiki/GitHub-Actions-Certification`).

| Workflow | Exam topic it teaches |
|----------|----------------------|
| `01-matrix.yml` | `strategy.matrix` — one job across many versions in parallel; `fail-fast` |
| `02-cache-artifacts.yml` | `actions/cache` (keyed restore/save) + upload/download artifacts across jobs |
| `03-reusable.yml` | Reusable workflow (`on: workflow_call`) with typed inputs + outputs |
| `04-caller.yml` | Calling a reusable workflow with `uses:` and consuming its output via `needs` |
| `05-concurrency-conditionals.yml` | `concurrency` (cancel-in-progress), `if:` + status functions, job outputs gating jobs |

Reference: [GitHub Actions docs](https://docs.github.com/actions).
