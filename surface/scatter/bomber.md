# Bomber

## Bomber

The Bomber node takes an input heightfield and "stamps" or bombs it across the entire surface of the terrain using the randomization properties you set.

If your terrain has a hard edge, you can turn on Fade Edges. Or for more precise control, try using the [edge.md](../../utility/structure/edge.md "mention") or [clip.md](../../modify/adjust/clip.md "mention")before applying the Bomber node.


# Properties

- **Iterations**: 
- **Multiplier**: 
- **Size**: 
- **Size Distribution**: 
- **Rotation**: 
- **Maintain Proportions**: 
- **Variable Height**: 
- **Height**: 
- Distribution
  - **Random**: A randomized distribution that results in pure chaotic patterns.
  - **Grid**: A normalized grid distribution function that results in a systematic pattern.
- **Jitter**: The random offset applied to each instance while distributing.
- **Seed**: The randomization pattern or seed for the node's process.
- **Fade Edges**: 
- Blend Mode
  - **None**: <desc>
  - **Blend**: <desc>
  - **Add**: Adds the two values together.
  - **Subtract**: <desc>
  - **Difference**:  Creates the difference of the two inputs.
  - **Multiply**: <desc>
  - **Screen**: Adds the two inputs without overexposing the output.
  - **Max**: Selects the higher of the two.
  - **Min**: <desc>
- Quality
  - **Draft**: <desc>
  - **Medium**: <desc>
  - **High**: <desc>
- **Add Input**: 