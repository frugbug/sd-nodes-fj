# sd-nodes-fj
Some custom nodes for Substance Designer

## Random switch
A node which will select an input based on random seed

## Luminance
Very accuarate colour to greyscale conversion. Intended to replace the Luma function of the stock node "Greyscale Conversion Advanced"

## Soft threshold
Basically the same thing as histogram scan, but more intuitive and easier to use

## Wood grain
Generates wood grain flowing in any direction. Not very good but can be used as a starting point

## Base material (Extra)
A modified base material node with some extra shader inputs, plus a preset for my own custom "clay" material I like to start with

## Empty Hald CLUT
Generates a blank/empty/plain/unmodified Hald CLUT

## Quick Colours
6 nodes which are basically presets for the uniform colour node. White, mid-grey and black (1, 0.5 and 0), in both colour and greyscale versions with lots of search tags. For example, "1g" will give you white in greyscale format. "0c" is black in colour format.

## Position remap
Kind of a novelty node. Will distort an input based on a position map, ~~haven't found a good use for it yet~~ I've found it useful when compositing renders, after rendering a separate UV pass. Applying an effect to a position map and using this node can produce different and interesting results than applying the effect to the input.

## Non-uniform Blackbody
Stock blackbody node with an input map instead of uniform temperature value - not too useful but could come in handy

# Meshes
**Big cylinder:** A big cylinder, a square material will wrap around it 6 times  
**Double big cylinder:** Same as big cylinder, but twice as tall  
**Cube (hi-res):** The default cube model but with extra geometry to allow the usage of the tesselation shader  
**Multi Mesh:** The amazing MultiMesh™! Rounded cube, rounded cylinder, 2-tiles sphere, upright plane and flat plane all rolled into one!  
**Thin cylinder:** A thin cylinder, a square material will only wrap around it once  
**Upright plane:** Just an upright plane  
