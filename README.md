# Denizen specific info
For now, it outputs the particle export as a ListTag of relative vectors, plug in your own starting location. Use it in something like this:
```
- define location <player.location>
- define list <paste the exported ListTag here>
- foreach <[list]> as:particle:
    - playeffect at:<[location].relative[<[particle]>]> effect:electric_spark count:1
```
# Particle Converter 
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/kemo14331/Particle-Converter)  [![GitHub license](https://img.shields.io/github/license/kemo14331/Particle-Converter)](https://github.com/kemo14331/Particle-Converter/blob/main/LICENSE)  
Particle Converter is an application to convert image files into particle commands.



## Screenshots
 ![screenshot0](https://imgur.com/HvnhBgF.jpg,"screenshot")
 <details>
 <summary>and more</summary><div>  
 <img src="https://imgur.com/Ld544Cx.jpg", "screenshot1">
 <img src="https://imgur.com/hdSbSkc.jpg" alt="screenshot2" />
 </div></details>  

## Features
* Convert the image file (.jpg|.png) into a particle command that can be displayed in Minecraft and output as a mcfunction format
* Correspond to world relative coordinates(~) and local relative coordinates(^).
* Real-time preview of parameter changes.
* Display size can be specified by block.
* Support for changing resolution.
* Supports the color specification of dust.
* Compatible with particles other than dust.
* Multi-language support for the app.

Translated with www.DeepL.com/Translator (free version)

## Requirement
 
 * .NETCore 3.1
 
## Library
 * [Material Design In Xaml](http://materialdesigninxaml.net/)
 * [OpenCVSharp4](https://github.com/shimat/opencvsharp)
 * [HelixToolkit.SharpDX.Core.Wpf](https://github.com/helix-toolkit/helix-toolkit) 

## Original Author

* Kemo431  
* Twitter: [@newkemo431](https://twitter.com/newkemo431)
