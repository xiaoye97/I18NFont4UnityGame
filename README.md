# I18NFont4UnityGame
**[中文文档](README_CN.md)**

I18NFont4UnityGame is a plugin I made for translate unity game, based on [BepInEx](https://github.com/BepInEx/BepInEx).

It can load custom font packages to fix the problem of missing fonts in the game.

## How to use

1. Install BepInEx for the target game

2. Clone repositories

3. Open with visual studio 2019

4. Modify the reference DLL according to the target game

5. Compile this plugin

6. Put the plugin into the GameName/BepInEx/plugins/I18NFont4UnityGame/ folder

7. Put the font package into the GameName/BepInEx/plugins/I18NFont4UnityGame/ folder

8. Modify the FontName value in the configuration file to the font name (if there is no configuration file, start a game to generate)

9. Enter the game

## Recommended font
- `Source Han Sans` Good looking fonts suitable for China, Japan, South Korea and other places [https://github.com/adobe-fonts/source-han-sans](https://github.com/adobe-fonts/source-han-sans)
- `Unifont` Applicable to almost all regions, but not very clear [http://unifoundry.com/unifont/index.html](http://unifoundry.com/unifont/index.html)

## How to make font package

To be added