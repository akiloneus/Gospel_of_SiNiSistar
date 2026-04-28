# Gospel of SiNiSistar
***Eat, Sleep, SiNi, Repeat.***

**SiNiSistar2 1周年おめでとう！**

This repo is for things I would like to share about the *SiNiSistar* game series (e.g., plugins and thoughts). I have learned a lot from them.

I am not sure if such behavior is endorsed by **Uu** (the doujin circle behind *SiNiSistar* series), but this is a way I express my love and passion for the series and the game industry. I hold the deepest admiration for the designer **Nennai** and the engineer **Miikun**.  

**For the developers of *SiNiSistar*:** I totally respect your work and intellectual property. If you have any concerns regarding this repo, please contact me, and I will take it down immediately. 


## Plugins
![GitHub release](https://img.shields.io/github/v/release/Akiloneus/Gospel_of_SiNiSistar)

I have built BepInEx plugins, primarily for *SiNiSistar2* in this repo, they may work in other Unity games as long as the compatible BepInEx is installed for the game. **Currently there are only versions for** [BepInEx-Unity.IL2CPP-win-x64-6.0.0-be](https://builds.bepinex.dev/projects/bepinex_be), which can be installed for *SiNiSistar2 (Win)*. 

The logic behind these plugins are straightforward; it's not rocket science. I may make them open-source as stand-alone plugins someday, but for now, please let me keep them proprietary for a while. 

**Current AkiTool includes:**

**[AkiCursorTool](https://github.com/akiloneus/Gospel_of_SiNiSistar/releases):** Hides, confines and locks the cursor at the center of screen. A customizable config would be generated under `\BepInEx\config\` after the first time loading the plugin.


**[MouseInputMapper](https://github.com/akiloneus/Gospel_of_SiNiSistar/releases):** Maps the mouse button and wheel input to keyboard keys, customizable. It is highly recommended to use together with AkiCursorTool, if the game application doesn't handle the cursor. 
This is somehow a workaround for games that mouse input is not supported. 
The config would be generated under `\BepInEx\config\` after the first time loading the plugin. 
> **Default Mapping:**
> * Mouse Left Click -> `Keyboard.X`
> * Mouse Right Click -> `Keyboard.Z`
> * Mouse Side Button Back -> `Keyboard.C`
> * Mouse Wheel Up -> `Keyboard.ArrowUp`
> * Mouse Wheel Down -> `Keyboard.ArrowDown`
>
> Note: Apparently it is optimized for *SiNiSistar2*. For other games or custom mapping, edit the config file manually. Note that a lot of games use `Keyboard.Z` as the confirm button, while *SiNiSistar2 uses* `Keyboard.X`

**How to install?**
1. Ensure the correct version of BepInEx (in this case BepInEx 6.x IL2CPP x64 Windows) is installed for the game.
2. Extract and put the plugin `.dll` into `\BepInEx\plugins\`.

## Articles
[Technical Analysis on Terrain Texture Normal Mapping](<SiNiSistar2/Insights/Technical Analysis on Terrain Normal Mapping - Cave Levels.md>) - May not that technical, but still inspiring in my opinion.

## Contact
akiloneus@outlook.com
