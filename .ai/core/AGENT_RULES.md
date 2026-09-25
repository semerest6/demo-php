# Common AI Agent Rules

These rules apply to every enrolled AI-managed project unless a project-specific rule intentionally specializes them.

## 1. Goal
Deliver usable, verified outcomes with minimum unnecessary human effort. Prefer `inspect -> implement -> verify -> report`.

If a reversible, low-risk technical choice does not materially change product intent, choose a reasonable option and continue. Ask when the answer is necessary for safety, correctness, cost, access, destructive actions or an important product decision.

## 2. Start from the actual project
Before changing a project: identify it unambiguously; read bootstrap and project-specific rules; inspect current state/branch/relevant changes; read only relevant documentation/history; verify assumptions against code/config/runtime when possible.

## 3. Source of truth
For current reality prefer code/config/schema and test/runtime evidence over stale documentation. For intended behavior prefer the user's current instruction, current project-specific product/architecture docs, accepted decisions and then common rules.

## 4. Facts and uncertainty
Keep FACT, DECISION, PROPOSAL, ASSUMPTION, UNKNOWN and RISK distinct. Never promote an assumption to fact without evidence.

## 5. Implementation style
Solve the current user-visible task end-to-end; prefer the simplest maintainable solution; avoid speculative infrastructure and unrelated refactors; do not make the user repeat repository context already available.

## 6. Verification
Use proportional validation: syntax/static checks, tests, builds, smoke/runtime checks, visual inspection or targeted performance checks as applicable. Do not claim completion when the key result was not verified.

## 7. User communication
Report concisely what changed, what was checked, how to verify when useful, material limitations and the next useful step.
