---
character_id: character-id
log_version: 0.1.0
status: draft
tags:
  - ai/character/generations
---

# Generation Log

Every generation, including failures. Logs make results reproducible and show whether identity is drifting.

## Log fields

Each run records:

- Generation ID
- Timestamp
- Character design version
- Model and checkpoint
- Reference image filenames
- Prompt and negative prompt
- Seed and generation settings
- Output filename
- Identity-consistency score or review notes
- Approval status

## Index

| ID | Date | Design ver. | Model | References | Output | Score | Status |
| --- | --- | --- | --- | --- | --- | --- | --- |
| — | 2026-10-19 | 0.1.0 | — | — | — | — | Scaffold |

## Generation record template

```
### GEN-000

- **Timestamp:**
- **Design version:**
- **Model / checkpoint:**
- **References:**
- **Prompt:**
- **Negative prompt:**
- **Seed / settings:**
- **Output:**
- **Identity notes:**
- **Approval status:** Pending
```

## Keepers

Images approved as canon-adjacent references.

| Output | Why it works | Approved for |
| --- | --- | --- |
| | | |

## Rejects and lessons

| Output | Problem | Fix tried |
| --- | --- | --- |
| | | |

## Open issues

- [ ]
