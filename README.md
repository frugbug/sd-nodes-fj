# sd-nodes-fj
Some custom nodes for Substance Designer

## Random Switch
A node which will select an input based on random seed.

## Preview
Plug a texture into this to show it in the 3D view without lighting. Especially useful when texturing a 3D mesh. Select the connection coming out of a node before creating this one to pass through the connection.

## Get Average
Returns the average value of a greyscale input.

## Rotate
Rotates the input around a point.

## Radial Offset
Offsets the input along a set direction.

## Grunge Master
A node for performing common tiling/upscaling operations on bitmap grunges to make them more generally useful.

## Soft Threshold
Basically the same thing as histogram scan, but more intuitive with less clutter and better defaults.

## UV Warp
Distorts the first input's UV coordinates based on the second input. Good for very low intensity warps as it does not produce noise, but will create visible stretching at high intensities.

## Scale & Bias
Similar to Unreal Engine's ConstantBiasScale shader node. Primarily made to remap \[0,1\] data to \[-1,1\]. Can be fun for directional warps.

## Wood grain
Generates wood grain flowing in any direction. Not fantastic but can be used as a starting point.

## Rock Generator
A rock generator with a few options. Everybody ends up making one of these at some point and this one is mine.

## Base material (Extra)
A modified base material node with some extra shader inputs, plus a preset for my own custom "clay" material I like to start with.

## Empty Hald CLUT
Generates a blank/empty/plain/unmodified Hald CLUT.

## Luminance
Very accurate sRGB colour to greyscale conversion. It's not super useful, but it's nicer to look at than other greyscale conversion methods.

## Non-uniform Blackbody
Stock blackbody node with an input map instead of uniform temperature value. You can choose to set an upper and lower value for the map, or you can plug an HDR map in directly.

## 8bitifier
Converts an input to 8bit, useful immediately before output nodes. Keeps file sizes down. Made this because it's quicker than dropping in any other node and fiddling with the bit depth dropdown.

## Icon Base
For creating icons for custom nodes, it generates a the grey/red checkered circles used in most stock node library icons.

## Pyramid Custom
Allows the user to choose a custom peak position for the pyramid.

## Material Blend Custom
Added an option to change normal blending mode (replace/combine) and added an opacity channel.

## Position remap
Kind of a novelty node. Will distort an input based on a position map, ~~haven't found a good use for it yet~~ I've found it useful when compositing renders, after rendering a separate UV pass. Applying an effect to a position map and using this node can produce interesting different results than applying the effect to the input.

## Quick Colours
6 nodes which are basically presets for the uniform colour node. White, mid-grey and black (1, 0.5 and 0), in both colour and greyscale versions with lots of search tags. For example, "1g" will give you white in greyscale format. "0c" is black in colour format.

# Meshes
**Big cylinder:** A big cylinder, a square material will wrap around it 6 times  
**Double big cylinder:** Same as big cylinder, but twice as tall  
**Cube (hi-res):** The default cube model but with extra geometry to allow the usage of the tessellation shader  
**Multi Mesh:** The amazing MultiMesh™! Rounded cube, rounded cylinder, 2-tiles sphere, upright plane and flat plane all rolled into one!  
**Thin cylinder:** A thin cylinder, a square material will only wrap around it once  
**Upright plane:** Just an upright plane  
