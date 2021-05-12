# 实验五：Android模拟器环境搭建

# 实验要求

- [x] 安装和配置 Java SDK

- [x] 安装Android Studio

- [x] 下载安装 Android SDK

- [x] 配置 Android 模拟器运行环境

- [x] 配置 Gradle 编译环境

# 实验环境

- Windows 10

- Java SE Development Kit 11

- Android Studio -  4.1.2 for Windows 64-bit

# 实验过程

## 安装和配置 Java SDK

前往[官方网站](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)下载SDK：

![](img/下载.jpg)

SDK安装完毕后，为了方便使用需要配置环境变量：

![](img/java.jpg)

在本机中查看是否配置成功：

![](img/SDK成功.jpg)

## 安装Android Studio

前往[官方网站](https://developer.android.com/studio)下载客户端，按需安装即可，过程就不详细截图了：

![](img/安装成功.jpg)

## 下载安装 Android SDK

通过启动界面的菜单选项 Configure -> SDK Manager 启动 SDK Manager:

![](img/打开.jpg)

选择Android 11.0版本的SDK，直接进行安装即可：

![](img/ASDK.jpg)

## 配置 Android 模拟器运行环境

安装Intel x86 Emulator Accelerator (HAXM installer)

![](img/工具.jpg)

可按需创建AVD：

![](img/模拟器.jpg)

模拟器实际运行的效果：

![](img/效果.jpg)

## 配置 Gradle 编译环境

查看Android Studio内置Gradle及其插件版本信息：

![](img/Gradle.jpg)

# 参考资料

[老师课本](https://c4pr1c3.github.io/cuc-mis/chap0x05/exp.html)