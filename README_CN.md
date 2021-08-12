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

待补充