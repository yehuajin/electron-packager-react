#
虽然electron-builder比electron-packager有更丰富的的功能。
支持更多的平台，同时也支持了自动更新，
electron-builder打出的包更为轻量，并且可以打包出不暴露源码的setup安装程序。
但是第一次打包nsis-resources必须下载，使用vnp也未能成功下载固使用electron-packager

#
由于没有Mac电脑测试，只在windows平台测试过

#运行如下命令
yarn // 安装依赖

yarn builder

yarn packageWin // 生成windows系统下的桌面应用

yarn packageDarwin // 生成os系统下的桌面应用

yarn packageLinux // 生成Linux下的桌面应用
