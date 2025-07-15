# Dilate

Dilate expands every pixel of your terrain or mask using the selected kernel or shape.



* **Size**\
  Sets the distance or radius of dilation. Larger values expand farther.
* **Shape**\
  Defines the overall shape of the dilation operation (e.g. circle, square).
* **Iterations**\
  Number of times to repeat the dilation. Higher values make the effect stronger or thicker.
* **Kernel**\
  Structuring element shape controlling the dilation pattern:
  * **Cross:** 4-connected cross-shaped kernel, good for plus-sign expansion.
  * **Rectangle:** Expands evenly in all directions with a rectangular pattern.
  * **Line:** Horizontal line kernel, expands only sideways.
  * **LineVertical:** Vertical line kernel, expands only vertically.
* **Invert**\
  Inverts the input before dilation, effectively shrinking bright regions instead of expanding them.
