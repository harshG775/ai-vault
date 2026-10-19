---
character_id: character-id
type: ai-character
status: draft
design_version: 0.1.0
visual_style: photorealistic
canonical_reference: "[[references/reference-index]]"
appearance_spec: "[[appearance/appearance]]"
master_prompt: "[[prompts/master-prompt]]"
created: 2026-10-19
updated: 2026-10-19
tags:
  - ai/character
---

# Character ID

## Overview

- **Character ID:** `character-id`
- **Display name:** TBD
- **Character type:** Original fictional character
- **Visual style:** Photorealistic
- **Design status:** Draft

## Design goals

Describe the intended visual identity and what makes this character recognizable.

## Canonical appearance

- **Face:** [[appearance/face]]
- **Hair:** [[appearance/hair]]
- **Skin:** [[appearance/skin]]
- **Body:** [[appearance/body]]
- **Overall appearance:** [[appearance/appearance]]

## Visual invariants

These features must remain stable across generations.

- Facial geometry
- Eye shape and color
- Nose and lip structure
- Skin tone and distinctive marks
- Hairline and base hair color
- Body proportions

## Permitted variations

These may change without redefining the character.

- Facial expression
- Pose and gesture
- Clothing and accessories
- Environment
- Lighting and camera angle

## Canonical references

See [[references/reference-index]].

## Generation

Use [[prompts/master-prompt]] as the base identity specification.

Add scene variables from [[prompts/scene-template]].

Record generation details and approval decisions in [[generations/generation-log]].

## Change control

Changes to canonical facial features, hair, or body proportions require an explicit design-version update and approval.

See [[CHANGELOG]] for design history.

## Related workspace

- **Wardrobe:** [[wardrobe/wardrobe]]
- **Expressions:** [[expressions/expressions]]
- **Generation log:** [[generations/generation-log]]
