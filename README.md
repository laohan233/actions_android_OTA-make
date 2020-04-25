# actions_android_OTA-make #

## 简介 ##
这是一个利用github actions自动化制作安卓OTA刷机包的脚本，使用Cjybyjk的OTA-maker源码：https://github.com/cjybyjk/OTA-maker 制作，在此表示感谢。

### 食用方法 ###
首先，fork这个仓库到你自己的账号下。  
接着，编辑.github/workflows文件夹下的.yml文件，将OLD_ROM_URL改成你需要制作OTA的旧包，将NEW_ROM_URL改成你需要制作OTA的新包，这里以红米7A的官方MIUI11为例。  
最后，仅仅需要按下Star小星星按钮，即可开始制作OTA刷机包。  
可以在Actions菜单下查看进度。
