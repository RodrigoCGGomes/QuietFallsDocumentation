---
tags:
  - ShaderDocumentation
---
This shader provides the same stylized look of the [[QF_MasterShader (Shader Documentation)|QF_MasterShader]] but if fully compatible with the Unity Terrain System.
## Properties

| Property        | Data Type   | Description                              | Default Value |
| --------------- | ----------- | ---------------------------------------- | ------------- |
| Basecolor       | Texture2D   | Texture map for the basecolor            | White if null |
| Color Tint      | Color       | Basecolor tint                           | White         |
| Roughness       | Texture2D   | Texture map for the reflection roughness | 0.6           |
| Normal Map      | Texture2D   | Texture map for the normals              | -             |
| [[Pink Factor]] | Float (0,1) | Stylized fleshy effect                   | 0             |

![QF_MasterShader_PinkFactor_Property.jpg](QF_MasterShader_PinkFactor_Property.jpg)
*Screenshot of the Unity inspector, displaying the properties in a material using this shader.*
## Dependencies
- ####  Cyanliux's URP_ShaderGraphCustomLighting
This unity package is required for this shader to work. It offers ShaderGraph's Sub Graphs that make it possible to gather shadow information in a Unlit Shader Graph. Without it, this shader wouldn't be able to support shadows. It also provides Lambert-cosine-law (Diffuse) calculation, fog sampler and some other features. ==Without this package the shader does not work==.
Also, the author offers different GitHub branches and often catches up with Unity's updates, so it's important to use the correct branch to avoid glitches and unexpected behavior.