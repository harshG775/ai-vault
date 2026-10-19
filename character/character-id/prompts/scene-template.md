---
character_id: character-id
prompt_type: scene-template
design_version: 0.1.0
status: draft
tags:
  - ai/character/prompts
---

# Scene Prompt Template

## Identity

Use the approved identity specification and reference images for [[../character]].

The identity block from [[master-prompt]] is fixed. This template only supplies the variables.

## Scene variables

- **Action / pose:** {{pose}}
- **Expression:** {{expression}}
- **Outfit:** {{outfit}}
- **Environment:** {{environment}}
- **Camera angle:** {{camera_angle}}
- **Shot size:** {{shot_size}}
- **Lighting:** {{lighting}}
- **Visual style:** {{visual_style}}

## Generation instruction

Change only the scene variables. Preserve the established character identity.

Check the generated image against the canonical references before approval.

## Assembly

```
[identity block from master-prompt]
[scene variables, filled in]
[selected canonical references]
```

## Example

```
standing in a rain-soaked alley at night, tense expression,
default outfit, neon signage and wet asphalt, low three-quarter angle,
medium shot, hard rim light from behind, photorealistic, teal and magenta grade
```

## Notes

- `{{variable}}` is a template convention. Obsidian does not substitute these without a plugin or script.
- Outfit changes must not alter body proportions.
- Expression changes must not alter facial geometry.
