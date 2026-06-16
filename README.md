# bot-smoke-test

Smoke test for the reusable bot workflows hosted in repo-template.

## Triggering pr-review
This line is added on a branch to open a PR and verify the reusable
`pr-review` bot runs end-to-end (caller stub -> reusable workflow ->
prompt from repo-template -> org LLM_* config).
