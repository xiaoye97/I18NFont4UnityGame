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

1. Install unity which is the same as the game version
2. Create a new project and install AssetBundleBrowser in PackageManager
3. Change the font file name you want to make into a font package to all lowercase
4. Put the font into unity
5. Select the font and right-click, select Create->TextSeshPro->Font Asset
6. Adjust TMP atlas settings, such as sampling rate, to achieve the desired effect
7. On the Inspector panel, set the AssetBundle name for the imported font and TMP font. The name should be all lowercase and consistent with the file name of the font
8. Open window - > Asset Bundle Browser to Package Fonts
9. Put the generated font package into the GameName/BepInEx/plugins/I18NFont4UnityGame/ folder

## Translation projects I participated

1. [VRoidChinese](https://github.com/xiaoye97/VRoidChinese)
2. [StarmancerChinese](https://youhanhua.com/527.html)