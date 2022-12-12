# Bure-Chan_Shader
Smart Shader that uses any of the RGBA channels of a Texture as Albedo, supports Blend Modes.

*(Sorry, no GIF available yet!)*
 
### Overview
 This Shader is based on the technique of combining multiple images/textures as R,G,B & A channels into a single Texture.
 In practice, each channel can be then repurposed as a gray-based Texture.
 So you can combine the texture information with a solid color.
 
### Guidelines
For the Texture to work please follow this guide: http://wiki.polycount.com/wiki/ChannelPacking

**NOTE:** This tool **will NOT** combine the texture for you. There are a few Image software that allow to combine multiple images into RGBA channels.
 
  
### Instructions
 1. Create a material that refers to **Evolis3D/Burechan**.
 2. Apply the material to any mesh you want.

### Current Features
 - Blend modes: *Multiply/Tint, Add, Overlay, Screen, Subtract*
 - Channel selector: Red, Green, Blue, Alpha.
 - Mix the desired texture with a color.

### Planned Features
 - Make a variant of the Shader that works on Sprites/UI.
 - Support for Gradients in addition to solid colors.
 - More Blend modes?
