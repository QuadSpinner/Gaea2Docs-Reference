# Thermal



Thermal simulates Thermal Erosion that can create talus and debris.

## Using Thermal Erosion

#### Selective Processing

Like with the @Erosion node, you can modulate how 

#### Thermal Stress Anisotropy
Thermal Stress Anisotropy governs how erosion and the resulting rocks deposits are shaped. It smooths the terrain while eroding. Low values keep the original terrain intact for the most part, while high values create stronger talus at the expense of eroding the original terrain. For example, sharp peaks get eroded heavily with high stress values.

The image below shows a simplified version of how Thermal Stress Anisotropy affects a terrain.

![](/images/thermal_stress_anisotropy.webp)


#### Combining with Hydraulic Erosion

In the real world, hydraulic and thermal erosion occur together. You can mimic this behavior by chaining @Thermal and @Erosion (or @Wizard) nodes, as shown in the Layering Erosion section in @erosions.

![Chained sequence of Wizard/Erosion and Thermal nodes](/images/ref/chain-thermal-erosion.webp)

Selective Processing can be a very powerful tool in such a chain of nodes, for both @Thermal and @Erosion.



# Properties


## Erosion

- **Duration**: Duration of the thermal erosion process.
- **Strength**: Strength of the thermal erosion process.
- **Anisotropy**: Thermal erosion's anisotropy that affects how rock is affected, and deposits formed. See the Anisotropy section for details.
- **Seed**: 

## Talus

- **Angle**: 
- **Settling**: 
- **Sediment Removal**: Amount of sediment to be removed.

## Scale

- **Feature Scale**: Scale of the largest feature in the terrain.
- **Real Scale**: Use the scale defined in the terrain. Disable to access addtional options and modify erosion's physics.
- **Terrain Scale**: Scale of the terrain. Available when Real Scale is turned Off
- **Verticality**: Height of the terrain.Available when Real Scale is turned Off



