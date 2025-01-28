---
title: 更简单的小企鹅 fcitx5输入法+白霜词库的搭配指南
date: 2024-12-15 10:25:40
tags: 记录
categories: 生活
description: "更简单的小企鹅 fcitx5输入法+白霜词库的搭配指南"

---

> 
>
> 小企鹅 fcitx5 输入法+白霜词库的搭配指南启发灵感来自 Up 主久光本光 [RIME 输入法+白霜词库配置教程](https://www.bilibili.com/opus/995633252409540613)

> ​        以下内容选自 up“久光本光”，简单方案：直接安装 [雨燕输入法]；手动方案：小企鹅输入法框架+Rime 插件，1. 需要安装两个 app，MT 管理器]和小企鹅输入法更新器]。

> ​       ※ 此处注意如果选择在更新更新器下载，那么输入法与插件都要在这上面下载。如果和我一样没有采用更新器，单独下载；那么两个都要网站单独下载。并安装。

<img src="./%E5%B0%8F%E4%BC%81%E9%B9%85fcitx5%E8%BE%93%E5%85%A5%E6%B3%95+%E7%99%BD%E9%9C%9C%E8%AF%8D%E5%BA%93%E7%9A%84%E6%90%AD%E9%85%8D%E6%9B%B4%E7%AE%80%E5%8D%95/q3ydcbrd.png" alt="cut-off" style="zoom:80%;" />

我的方法

不需要额外安装 MT 管理器

​       首先更新的最新版小企鹅输入法 0.1.0-14-g66994206 版，可以直接进入数据文件夹。

​       演示用手机 （Android13、HyperOS 1.0.5.0 、骁龙 865）

如果和我一样没有采用更新器，并提前已经在使用小企鹅

需要单独下载并安装小企鹅 rime 插件（fcitx5-android-plugin-rime）

这里插件安装和普通安卓软件安装一样。

插件下载地址：[https://jenkins.fcitx-im.org/job/android/job/fcitx5-android-plugin-rime/]

返回小企鹅输入法打开如图设置点击插件，它会提示刷新，点击刷新即可，然后

1、点击设置

<img src="./%E5%B0%8F%E4%BC%81%E9%B9%85fcitx5%E8%BE%93%E5%85%A5%E6%B3%95+%E7%99%BD%E9%9C%9C%E8%AF%8D%E5%BA%93%E7%9A%84%E6%90%AD%E9%85%8D%E6%9B%B4%E7%AE%80%E5%8D%95/sz.avif" alt="cut-off" style="zoom:50%;" />

2、点击 高级

<img src="./%E5%B0%8F%E4%BC%81%E9%B9%85fcitx5%E8%BE%93%E5%85%A5%E6%B3%95+%E7%99%BD%E9%9C%9C%E8%AF%8D%E5%BA%93%E7%9A%84%E6%90%AD%E9%85%8D%E6%9B%B4%E7%AE%80%E5%8D%95/gj.jpg" alt="cut-off" style="zoom:50%;" />

3、点击  Browse user data directory

<img src="./%E5%B0%8F%E4%BC%81%E9%B9%85fcitx5%E8%BE%93%E5%85%A5%E6%B3%95+%E7%99%BD%E9%9C%9C%E8%AF%8D%E5%BA%93%E7%9A%84%E6%90%AD%E9%85%8D%E6%9B%B4%E7%AE%80%E5%8D%95/bud.jpg" alt="img" style="zoom:50%;" />

4、如图进入到数据目录（如下图）

​         可以在此处先点进 data 文件夹内，如果没有 rime 文件夹，请手动新建。

（这样后续可以直接复制文件到此目录内的 data 文件夹）

<img src="./%E5%B0%8F%E4%BC%81%E9%B9%85fcitx5%E8%BE%93%E5%85%A5%E6%B3%95+%E7%99%BD%E9%9C%9C%E8%AF%8D%E5%BA%93%E7%9A%84%E6%90%AD%E9%85%8D%E6%9B%B4%E7%AE%80%E5%8D%95/data.webp" alt="img" style="zoom:50%;" />

 5、下载白霜词库

​       并解压到手机的 Download 文件夹（这里以 Download 文件夹为例，方便找到）

白霜词库下载地址：[https://github.com/zjralhf/rime--] 

或 [https://gitee.com/chunqiu123456/rime-frost]

然后点击上图中右上角三条横线后转变为（如下图）状态

<img src="./%E5%B0%8F%E4%BC%81%E9%B9%85fcitx5%E8%BE%93%E5%85%A5%E6%B3%95+%E7%99%BD%E9%9C%9C%E8%AF%8D%E5%BA%93%E7%9A%84%E6%90%AD%E9%85%8D%E6%9B%B4%E7%AE%80%E5%8D%95/xz.png" alt="img" style="zoom:50%;" />

6、点击“下载内容”按钮直接跳转到 Download 文件夹内



将解压好的白霜词库（rime---master 文件夹内的）所有文件复制粘贴到 rime 文件夹内。然后重启输入法等待几秒生效。

在设置里选“输入法” 添加“中洲韵”。

回到输入法打字的界面 点击剪切板符号旁的三个点进入设置页面点击“重载配置”。等待生效。此处第一次设置会卡一下。请等待一会，让它生效。

完成。
