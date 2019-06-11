---
title: VSCode 编辑器
date: 2018-06-06 14:23:25
tags:
---

### VSCode 简介

#### VSCode 是什么

Visual Studio Code（简称 VSCode ）是一个轻量但非常强大的代码编辑器，开源免费，适用于 Windows、macOS 和 Linux 系统。它内置了对 JavaScript ，TypeScript 和 Node.js 的支持，并为其他语言（如 C ++，C＃，Java，Python，PHP，Go 等）提供了丰富扩展插件。

### VSCode 具有一下几个优点：

代码智能补全：可补全变量、方法名、和导入模块名称等。

易于调试：不再需要打印调试，可直接使用 VSCode 中的终端工具进行调试。

强大的编辑功能：具有多光标编辑、格式调整、参数提示等编辑功能。

易于源码阅读：能快速定位到代码定义的位置，助于快速浏览代码。

### 安装

VSCode 支持跨平台安装，支持 macOS、Linux、Windows 系统。安装方式非常简单，在 VSCode 下载页选择适用你的操作系统的下载包，按照图形化界面的提示安装即可。

### 用户界面

VSCode 的用户界面和传统的编辑器类似，在左侧显示文件和文件夹目录，在右侧显示编辑区并显示已打开的文件。布局直观简单，易于上手。

![图片来自 VSCode 官网](https://code.visualstudio.com/assets/docs/getstarted/userinterface/hero.png)

用户界面分为六块区域：

- 编辑区：文件编辑区域，可以纵向、横向并排打开任意数量的编辑区。

- 侧边栏：上图 B 区，包含资源管理器等不同的视图，可以方便的处理项目中的文件。

- 状态栏：上图 E 区，展示已打开项目和编辑的文件信息。

- 活动栏：上图 A 区，可切换视图查看项目信息，例如文件内容搜索、Git 信息等都可以在活动栏查看。

- 面板区：上图 D 区，可以切换不同的面板显示调试信息、错误和警告或集成终端等。

- 编辑组：上图 C 区，可以拆分编辑器，成为一个编辑组，可以同时容纳多个编辑区域。

#### 安装 code 命令

VSCode 安装成功后，推荐安装 code 命令，使用 code 命令的方式进行各类文件操作能大大提高工作效率。在 macOS 上安装和使用 code 命令的姿势如下：

- 使用 shift + command + p 快捷键打开命令面板

- 输入 code，选择 shell 命令: 在 path 中安装"code 命令"

- 编辑器要求使用管理员权限，输入管理员密码

- 安装成功，编辑器提示 shell 命令已经安装成功

#### 终端 terminal 的使用

code 命令安装完成后就可以在终端中使用 code 命令了：

- ctrl + ` 打开终端 (终端打开快捷键会在下文【快捷键】章节说到)

- 在 terminal 中使用 code 命令，可以使用 code -h 查看 code 命令的用法；code -a demo.js 在当前文件夹下添加 demo.js 文件；code demo.js 在编辑器中打开 demo.js 文件等。还支持查看文件 diff、打开文件并定位光标到第 n 行等操作。

- VSCode 的终端使用命令的方式与计算机终端相似，除了可使用上述 code 命令以外，还可使用计算机自带的终端命令、git 命令（如果已安装 git）、npm 命令（如果已安装 npm）等。

### VSCode 设置

#### VSCode 设置包括两方面：

- 用户设置 User Setting：适用于当前用户打开的所有文件。

- 工作空间设置 Workspace Setting：只适用于当前文件夹，在当前文件夹下会有一个.vscode 隐藏文件，里面有一个 setting.json 文件保存工作空间设置，工作区间设置会覆盖用户设置。

VSCode 的设置姿势：

- 使用 shift + command + p 快捷键打开命令面板。

- 输入 Preferences 可选择 Preferences: Open User Settings 或 Preferences: Open Workspace Settings 进行用户设置或工作空间设置。

#### 快捷键设置

好用的编辑器少不了快捷键加成，vscode 设置快捷键十分方便，调出命令面板，输入关键字 open keyboard shortcuts，就可以调起快捷键设置页面，即可通过当前视图设置快捷键，也可以通过 keybindings.json 修改快捷键。

其中打开终端的快捷键、打开调试控制台的快捷键都可通过次方式设置。

介绍几个常用的快捷键：

command + d，一次是选择当前单词，两次则选中当前单词下次出现的地方；也可在选中了一段文本后进行 command + d，则可选中该文本下次出现的地方可。通过此方法进行多光标编辑，巨好用

command + i，选中当前行

command + /，快速注释或快速取消注释

快捷键太多，建议先 command + k 再 command + s，打开快捷键设置自己查看

### 插件

VSCode 的优点在于轻量，它不像传统的编辑器包含许多繁琐的功能，它只包含最基础的功能例如：编辑、文件管理、视窗管理和编好设置等。内置了对 JavaScript，TypeScript 和 Node.js 的支持。

除此之外，不同的用户可以根据自己的需求安装不同的 VSCode 插件。在最左侧活动栏，点击插件按钮，可以看到插件信息，并可搜索自己想要的插件，进行安装。VSCode 社区中已经维护了数百个插件供你选择。包括但不仅限于以下几个常用的插件：

- 语言相关：C++, C#, Go, java, python

- 开发工具相关：ESLint, JSHint, PowerShell

- debugger：debuge for chrome, PHP Debug

- 编辑风格：Vim, Sublime Text, IntelliJ IDEA, Emacs, Atom, Visual Studio, Eclips

### 总结

本节介绍了 VSCode 是什么、如何安装、用户界面的使用以及插件，更多具体用法还需使用者自己去发现探索。关于开发工具，选择适合自己代码习惯的开发工具即可，大可不必太过跟风，跟着自己感觉走最重要。

参考链接：

- [VSCode 官方文档](https://code.visualstudio.com/docs)
