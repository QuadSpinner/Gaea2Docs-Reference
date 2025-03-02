# Bomber

## Bomber

### Bomber

The Bomber node takes an input heightfield and "stamps" or bombs it across the entire surface of the terrain using the randomization properties you set.

If your terrain has a hard edge, you can turn on Fade Edges. Or for more precise control, try using the [edge.md](../../utility/structure/edge.md "mention") or [clip.md](../../modify/adjust/clip.md "mention")before applying the Bomber node.

## Properties

* **Iterations**: Number of instances the bombing operation will create.
* **Multiplier**: Quickly multiply the instances by increasing or decreasing this value.
* **Size**: The minimum and maximum relative size of bombed instances.
* **Size Distribution**: Uniformity of the size of the bombed instances.
* **Rotation**: The minimum and maximum range of rotations for the bombed instances.
* **Maintain Proportions**: Whether instances should maintain height vs size proportion or not.
* **Variable Height**: Allow variations in Height.
* **Height**: The minimum and maximum range of height variations for the bombed instances.
* Distribution
  * **Random**: A randomized distribution that results in pure chaotic patterns.
  * **Grid**: A normalized grid distribution function that results in a systematic pattern.
* **Jitter**: The random offset applied to each instance while distributing.
* **Seed**: The randomization pattern or seed for the node's process.
* **Fade Edges**:
* Blend Mode
  * **None**: Overwrite each instance.
  * **Blend**: Blend instances.
  * **Add**: Adds instances on top.
  * **Subtract**: Subtract each instance from the base and previous instances.
  * **Difference**: Create difference between the base and each bombed instance.
  * **Multiply**: Multiply the base with each bombed instance.
  * **Screen**: Adds the two inputs without overexposing the output.
  * **Max**: Retain the maximum height values of each bombed instance.
  * **Min**: Retain the minimum height values of each bombed instance.
* Quality
  * **Draft / Medium / High**: The level of quality to be used. Draft is recommended when working with high-resolution previews.
