# Contract

## Capability
Assess notebooks for hidden state, hard-coded paths, missing tests, data leakage and productionization blockers.

## Input root
`findings` with fields: cell, severity, users_affected, confidence.

## Output
JSON containing `skill` and deterministic findings, ranking, mapping, plan or redaction results.

Reject malformed JSON. Do not infer authorization or fabricate evidence.
