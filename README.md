# Solve PR review pilot

This public repository tests record-only pull-request adjudication with a Tangle agent graph.

Problem marker: `solve-pr-review-pilot-v1`

## Task

Read the three integers `19`, `22`, and `31`. Submit their sum modulo `97` in `submissions/solution.json`:

```json
{
  "challenge": "sum-mod-97",
  "answer": 0
}
```

Replace `0` with the answer. The base-owned evaluator is the only authority for the deterministic result. Reviewer agents assess the bounded evidence but cannot merge, close, comment, or label pull requests.

This pilot performs no GitHub mutations beyond the manually prepared test pull requests.
