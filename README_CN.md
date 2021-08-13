# I18NFont4UnityGame

I18NFont4UnityGame是我为了汉化Unity游戏所制作的插件，基于[BepInEx](https://github.com/BepInEx/BepInEx)框架。

它可以加载自定义的字体包，用于弥补游戏内字库不全的问题。

## 如何使用

1. 为目标游戏安装BepInEx
2. Clone本仓库
3. 使用VisualStudio2019打开
4. 根据目标游戏修改引用dll
5. 编译此插件
6. 将此插件放入 GameName/BepInEx/plugins/I18NFont4UnityGame/ 文件夹
7. 将目标字体放入 GameName/BepInEx/plugins/I18NFont4UnityGame/ 文件夹
8. 修改配置文件中的FontName值为字体名字(如果没有配置文件，启动一次游戏以生成)
9. 进入游戏

## 推荐字体
- `思源黑体` 适用于中国日本韩国等地的比较好看的字体 [https://github.com/adobe-fonts/source-han-sans](https://github.com/adobe-fonts/source-han-sans)
- `Unifont` 适用于几乎所有地区，但是不太清晰 [http://unifoundry.com/unifont/index.html](http://unifoundry.com/unifont/index.html)

## 如何制作字体包

1. 安装与游戏版本相同的Unity
2. 新建一个项目，在PackageManager安装AssetBundleBrowser
3. 将想要做成字体包的字体改名为全小写
4. 将字体放入Unity
5. 选中字体，右键Create->TextMeshPro->Font Asset
6. 调整TMP图集设置，如采样率等，以达到自己想要的效果
7. 在Inspector面板为导入的字体和TMP字体设置AssetBundle名，名字要全小写，和字体的文件名一致
8. 打开Window->Asset Bundle Browser，打包字体
9. 将生成的字体包放入 GameName/BepInEx/plugins/I18NFont4UnityGame/ 文件夹

## 我参与的汉化项目

1. [VRoidStudio汉化](https://github.com/xiaoye97/VRoidChinese)
2. [星际漫游者汉化](https://youhanhua.com/527.html)