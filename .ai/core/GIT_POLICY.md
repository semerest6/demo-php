# Common Git Policy

Inspect branch/status before repository changes. Do not overwrite unrelated or uncommitted work. Never commit credentials, tokens, private keys, .env content or real sensitive customer data. Never force-push, destructively reset or rewrite shared history unless explicitly requested and understood.

Treat the default branch as stable unless project rules state otherwise. Project-specific rules control whether AI may create branches automatically. If several candidate working branches exist and the correct one cannot be determined safely, ask.

Keep commits coherent. Files under `.ai/core/` are centrally managed by ai-workflow-core and should not be edited locally.
