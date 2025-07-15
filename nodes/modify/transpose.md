# Transpose

### Transpose

Transpose takes the character of the Reference terrain and applies to to the Input terrain. It maintains the original volume and shape of the Input terrain so you do not lose your silhouette, but still adds the details of the Reference terrain.

In practical scenarios, it is often difficult to create the kind of surface on a specific terrain. So you can create a basic terrain with low or no details, and then create flat (or undulating) surface separately, then Transpose the details onto your basic terrain.

This also works quite well with imported terrains or even meshes.

By combining Mask and Draw, you can [paint your effect](https://www.youtube.com/watch?v=mavy7rFpY9s) area.

### Embed



### Insert

Insert is a utility node that lets you insert a sparse heightfield into another heightfield while preserving the target heightfield's relative heights. A common example is creating rocks on a flat (clipped) surface and then inserting them onto a terrain. Unlike Max or Add combines, Insert preserves the inserted heightfield and does not add artifacts or shapes from the underlying heightfield.



* Mode
  * **Transpose**:
  * **Embed**:
  * **Insert**:
* **Amount**:
* **Extend**:
* **Flatten**:
* **Threshold**:
* **Boundary**:
