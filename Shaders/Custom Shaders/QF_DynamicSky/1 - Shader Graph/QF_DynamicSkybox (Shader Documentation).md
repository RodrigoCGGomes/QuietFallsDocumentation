---
tags:
  - ShaderDocumentation
---
==WORK IN PROGRESS - This Documentation is missing a lot of information==

Quiet Falls has a stylized look, shadows should not be as dark as the Unity's default lit shader. So this shader replaces the Unity's default lit shader.
Creating a custom shader for the game, gives the developer more control over the look of the game. 

## Properties

| Property  | Data Type | Description                   | Default Value |
| --------- | --------- | ----------------------------- | ------------- |
| Basecolor | Texture2D | Texture map for the basecolor | White if null |

![QF_DynamicSky_Inspector.jpg](QF_DynamicSky_Inspector.jpg)
*Screenshot of the Unity inspector, displaying the properties in a material using this shader.*

## Dependencies
- ####  