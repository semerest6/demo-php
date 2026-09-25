# Project Memory Policy

Project memory lets a new AI session continue meaningful work without making the user repeat important context.

Preserve project-relevant requirements/corrections, accepted decisions, completed implementation, verified results/failures, important risks, unresolved questions and the next concrete step.

Prefer: `request -> decision/interpretation -> work/result -> checks -> next step`.

Do not automatically preserve greetings, unrelated personal discussion, secrets/credentials, raw customer documents, large logs/screenshots or hidden reasoning.

Each project owns its own history. Never centralize project conversation history in ai-workflow-core.
