# Gospel of SiNiSistar
Eat, Sleep, SiNi, Repeat.

This repo is for things I would like to share about the *SiNiSistar* game series, e.g., plugins and thoughts. I have learned a lot from it.

I am not sure if this is endorsed by Uu, the doujin circle that develops the SiNiSistar series, but this is a way I express my love and passion for *SiNiSistar* and the game industry. I admire the designer Nennai and the engineer Miikun.  

**For the developers of *SiNiSistar*:** I totally respect your work and intellectual property. If you have any concerns regarding this repo, please contact me, and I will take it down immediately. 


## Plugins
![GitHub release](https://img.shields.io/github/v/release/Akiloneus/Gospel_of_SiNiSistar)

I have built BepInEx plugins, primarily for *SiNiSistar2* in this repo, they may work in other Unity games, as long as the compatible BepInEx is installed for the games. Currently there are only versions for [BepInEx-Unity.IL2CPP-win-x64-6.0.0-be](https://builds.bepinex.dev/projects/bepinex_be), which can be installed for *SiNiSistar2 (Win)*. 

**[AkiCursorTool](https://github.com/akiloneus/Gospel_of_SiNiSistar/releases)**: Hide, confine and lock the cursor at the center of screen. A customizable config would be generated under `\BepInEx\config\` after the first time loading the plugin.


**[MouseInputMapper](https://github.com/akiloneus/Gospel_of_SiNiSistar/releases)**: Map the mouse button and wheel input to keyboard keys, highly customizable. 

This is somehow a workaround for games that don't support mouse input. 

The config would be generated under `\BepInEx\config\` after the first time loading the plugin. 

**Default Mapping:**
- Mouse Left Click -> `Keyboard.X`
- Mouse Right Click -> `Keyboard.Z`
- Mouse Side Button Back -> `Keyboard.C`
- Mouse Wheel Up -> `Keyboard.ArrowUp`
- Mouse Wheel Down -> `Keyboard.ArrowDown`

(Apparently it is now optimized for *SiNiSistar2*. For other games or custom mapping, editing the config file manually is required. A lot of games use Keyboard.Z as the confirm button, while SiNiSistar uses Keyboard.X)

**How to install?**
1. Ensure the correct version of BepInEx (in this case BepInEx 6.x IL2CPP x64 Windows) is installed for the game.
2. Extract and put the plugin `.dll` into `\BepInEx\plugins\`.

## Articles
[Technical Analysis on Terrain Normal Mapping](<SiNiSistar2/Insights/Technical Analysis on Terrain Normal Mapping - Cave Levels.md>)
