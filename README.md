# never-commit-ai-artifact

Install the global Git hook:

```sh
./scripts/install-global-hook
```

The hook rejects commits containing files under `docs/superpowers/` or
`.superpowers/` across all repositories using the global Git hooks path.
