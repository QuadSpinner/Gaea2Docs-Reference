# TextureBase

Creates a mask simulating natural material distribution onto which color from [satmap.md](../colorize/satmap.md "mention") or [cluter.md](../colorize/cluter.md "mention") or other color node is “flowed.” Useful for driving texturing, shading, or erosion masks with a natural, layered look.

{% include "../../.gitbook/includes/color-lookup.md" %}

## Properties

* **Slope**\
  Controls how strongly the mask aligns to steeper slopes. Higher values favor cliffs and ridges.
* **Flows**\
  Simulates erosion-like flow patterns. Higher values create streaked, directional buildup.
* **Soil**\
  Adds soil-like accumulation in flatter areas, filling low spots and valleys.
* **Patches**\
  Introduces broken, patchy variations for a more natural, less uniform mask.
* **Chaos**\
  Adds randomized noise and breakup to reduce uniformity and increase realism.
* **Accentuate**\
  Enhances contrast within the mask, making features more pronounced.
* **Seed**\
  Controls the random variation. Changing the seed alters the pattern without changing other settings.
