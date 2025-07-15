# Filter

The Filter node shapes the terrain’s frequency content using an audio-inspired parametric filter. Useful for isolating or suppressing features at specific scales.

## Properties

* Mode
  * **LowPass:** Allows only low frequencies (large-scale features) to pass. Removes fine details.
  * **HighPass:** Allows only high frequencies (small-scale details) to pass. Removes broad shapes.
  * **LowShelf:** Boosts or cuts all frequencies below the selected frequency with a gentle slope.
  * **HighShelf:** Boosts or cuts all frequencies above the selected frequency with a gentle slope.
  * **BandPass:** Passes only a narrow band of frequencies around the selected center. Blocks both lower and higher frequencies.
  * **Notch:** Sharply removes a narrow frequency band. Ideal for cutting specific scale artifacts.
  * **Bell:** Bell-shaped EQ mode for boosting or cutting a selected frequency band more smoothly.
* **Frequency**: Sets the center frequency (scale) to target. Lower values affect broad, large-scale features; higher values focus on fine detail.
* **Gain**: Controls the strength of boost or cut. Positive values amplify the selected frequency; negative values reduce it.
* **Q**: Adjusts the sharpness or width of the filter. Low Q = broad, gentle slope. High Q = tight, precise filtering.
* **Keep DC**: When enabled, preserves the overall elevation offset (DC component) of the terrain, preventing unwanted flattening or vertical shifting.

