---
character_id: character-id
prompt_type: identity
design_version: 0.1.0
status: draft
tags:
  - ai/character/prompts
---

# Master Identity Prompt

## Instructions

Use the approved canonical references from [[../references/reference-index]].

Reproduce the same fictional character. Preserve facial geometry, eye shape and color, nose, lips, skin tone, hairline, hair color, distinctive marks, and body proportions.

The written appearance specification is the source of truth for descriptive features. Approved reference images are the source of truth for their visual realization.

Do not redesign the character while changing the scene.

## Character identity

Insert the approved description from the appearance specifications:

- Face: [[../appearance/face]]
- Hair: [[../appearance/hair]]
- Skin: [[../appearance/skin]]
- Body: [[../appearance/body]]

```
[character-id], [age appearance] [gender presentation],
[face shape] face, [eye shape and color] eyes, [nose], [lips],
[hair color, texture, length, parting], [skin tone and undertone],
[height and build], [distinctive marks],
```

## Fixed identity constraints

- Preserve the same face.
- Preserve eye shape, spacing, and color.
- Preserve nose and lip structure.
- Preserve skin tone and distinctive marks.
- Preserve the hairline and base hairstyle.
- Preserve body proportions.

## Quality constraints

- Natural, coherent anatomy
- Consistent age appearance
- No unintended identity changes
- No unexplained changes to signature features

## Reference requirements

Attach or select the canonical references supported by the generation tool. A text description alone is not a substitute for visual references.

## Negative prompt

```
low quality, blurry, deformed anatomy, extra fingers, inconsistent face,
wrong eye color, wrong hair color, changed skin tone, different person,
text, watermark, signature
```

## Usage

1. Start with this identity block and the canonical references.
2. Add scene variables from [[scene-template]].
3. Evaluate the result against [[../references/reference-index#Approval criteria|approval criteria]].
4. Record the generation in [[../generations/generation-log]].

## Revision notes

| Date | Design version | Change | Reason |
| --- | --- | --- | --- |
| 2026-10-19 | 0.1.0 | Initial prompt scaffold | — |
