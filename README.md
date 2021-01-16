# ue4_game_pak_key
ue4 pak aes key crypto

https://github.com/allcoolthingsatoneplace/UnrealPakTool
打开unrealpaktool。
把key放到crypto.json里。把pak放进目录，再双击UnrealPakExtractCrypto.bat解包。
这是一次性将pak全部提取。

也可以用unrealpakviewer单独提取。有gui界面。
https://github.com/jashking/UnrealPakViewer


pak就是个压缩包，游戏引擎将游戏文件打包在一起。解包就是解压缩。

得到的文件已经经过引擎处理，还不能直接用。

需要用umodel再提取。可以获取模型，贴图，音乐等。
https://github.com/gildor2/UEViewer

方便大家做同人作品。

MOD制作就是再多一步封包。
原理就是用你改的新文件去顶替原文件。

将你修改后的文件，用u4pak封包。
https://github.com/panzi/u4pak

注意文件目录要一样。
文件夹~mod
文件名XXX_P.pak 。加P是保证文件优先加载。
