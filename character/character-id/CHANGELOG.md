# Changelog — character-id

All notable design and structural changes. Newest first.

## Version scheme

| Version | Meaning |
| --- | --- |
| `0.1.0` | Initial draft |
| `0.2.0` | Approved design refinement |
| `1.0.0` | Canonical identity approved |
| `1.1.0` | Minor appearance-spec update that preserves identity |
| `2.0.0` | Intentional redesign of the canonical identity |

## 2026-10-19 — 0.1.0

- Created character workspace and folder structure.
- Added identity file, appearance specification, reference index, wardrobe, expressions, prompt templates, and generation log.
- Established source-of-truth split: specs describe features, approved images define their visual realization.
- Added design-version and change-control conventions.

### Files

- `character.md`
- `appearance/` — appearance, face, hair, skin, body
- `references/` — reference index and canonical image placeholders
- `wardrobe/wardrobe.md`
- `expressions/expressions.md`
- `prompts/` — master prompt and scene template
- `generations/generation-log.md`

<!--
Format for new entries:

## YYYY-MM-DD — X.Y.Z
- Changed:
- Why:
- Files:
- Approved by:
-->
