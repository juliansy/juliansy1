# 介绍

此项目源自对[Bilibili-Evolved](https://github.com/the1812/Bilibili-Evolved)脚本的一项功能的补充。

使用该脚本在用 **aria2 PRC 中的 dash**方式导出视频时，将会导出视频文件和音频文件。

本项目旨在借用 **FFmpeg** 用一个 **bash** 脚本**无损**合并这两个文件。

**由于是使用 bash 语句编写，仅支持 Windows 环境**

# 使用

-- 下载安装 **FFmpeg** ，并将其添加到 **PATH**。

-- 将脚本文件 “合并音频视频.bat” 放于所需合并文件的目录下

-- 单击脚本文件。

# 原理

脚本将会遍历当前目录下所有 “.mp4” 文件，对于每个 “.mp4” 文件，如果存在同名的 “.m4a” 文件，则调用 **FFmpeg** 将这两个文件合并为同名的 “.mkv” 文件。

# 声明

本项目使用 **FFmpeg** 和 **bash** 实现功能。
