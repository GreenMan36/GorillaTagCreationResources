# Shader Resources
>Listed from most useful, imo

### About these shader files
---
Shader files are pieces of code that tell the engine _(Unity)_ how to render an object. It contains info about how lights interact, if lights even interact, if something should be rendered in-front or behind some things, if it uses colors or textures and way more.

You might use one shader for multiple objects, so a material contains info about what texture to use or what color to use. This is info you can edit in the engine. The shaders themselfs you cannot, you need code for that. Or you can use ShaderForge.

Some shaders are hosted in this folder for you to use Info about them might come later in this readme.
### Shaderforge, node based shader editing
---
ShaderForge is a tool that helps you make shaders using a visual node-style based editor as seen in programs like Blender. You can get [ShaderForge Here](https://github.com/FreyaHolmer/ShaderForge/archive/refs/heads/sf_1.40_for_unity_2019.x.zip) To install ShaderForge you should copy the contents of the ShaderForge folder into the root of your GT project and make sure to **not overwrite** any files. Note that it still might be very complicated to make cool shaders even though you have ShaderForge. Shaders aren't easy and even with the load of tutorials out there it might be hard to get used to. Its recommended to search for ShaderForge specific tutorials and learn some basics about shaders. Some of the shaders that are shared can be edited with ShaderForge aswell, so you can modify them if you need to.

### Shader coding and shader samples
---
[ShadersLab has great example shaders](http://www.shaderslab.com/shaders.html) Recommended to check out if you want to code your own shaders but also if you need a few example shaders.

### Often used shaders we didn't ask to be able to include yet.
---
 - This [shader for worldborders](https://cdn.discordapp.com/attachments/813212277833465879/823747034342621204/AlphaDependingDistance_1.shader) can scroll, use custom textures and tile. And is often used for custom maps, its invisible untill you get close (distance configurable).

- This [Scrolling texture shader, follows UV's](https://discord.com/channels/810644499763691540/810663983106621501/837442033055432735) and can for example be used for rivers or other things that need a scrolling texture along a path. Note that it is code so you just need to paste it into a shader file, but no coding should be required. Just `CTRL+C` > `CTRL+V`.

### Generate normals
---
You can use [NormalMap Online](https://cpetry.github.io/NormalMap-Online/) if you feel the need to generate normals. Normals can be used to add more lighting info to your mesh. Although GT often doesn't need it or it just doesn't work too great with the low-res pixelated textures.
There are a load more tools online that can do the same but give slightly different results.