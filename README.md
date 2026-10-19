# promptregress-prompt-snapshot-testing
A lightweight test runner for LLM prompts. Users define prompts, inputs and assertions in YAML (contains, regex, JSON schema, LLM-judge). It caches responses, diffs outputs between prompt or model versions, and fails CI on regressions.
