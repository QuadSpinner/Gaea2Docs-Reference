# Texturizer

Works like **TextureBase** but uses pre-defined, curated profiles to quickly generate natural-looking texture masks. It’s designed for fast, consistent results with less manual tuning. **Factor** is the main strength or intensity control for the chosen style, while **Secondary** adjusts the impact of supporting details and effects

## Properties

* **Style**\
  Select from **A, B, C, D, E, F, G, H, I, J, K, L**, each representing a different pre-defined texture style. Experiment to find the look that best fits your terrain.
* **Factor**\
  Primary driver controlling the overall strength or intensity of the selected style.
* **Secondary**\
  Adjusts the strength of secondary effects like soil accumulation, flow streaks, and breakup patterns.
* **Seed**\
  Randomizes the pattern while keeping other settings the same for variation without re-tuning.

### Components

* **Flows**\
  Simulates natural erosion channels and directional streaks.
* **Slope**\
  Adds slope-based weighting to favor steeper or flatter areas.
* **Soil**\
  Controls soil-like accumulation in flatter regions, adding natural buildup.
