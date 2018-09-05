## 文本制作   
1. 直接使用 Excel 对 zh-Hans.csv 文件进行汉化。
2. 修改 speechBubbleConfig.ini 对文本的显示效果进行微调。

## 字库制作
1. 将 zh-Hans.csv 文件重命名为 Translations.csv 文件，并覆盖游戏原文件。
2. 利用游戏自带 Localization.exe 生成 Spritefont 文件。
3. 利用 XNAContentCompiler 按照 Spritefont 文件的逻辑生成 Xnb 字库文件。

## 图片制作
1. 图片直接使用PS进行修改。