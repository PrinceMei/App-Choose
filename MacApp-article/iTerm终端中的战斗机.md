# iTerm终端中的战斗机

# 前言

> sudo i Love this app

被誉为最强大的Mac终端工具 这篇文章负责收录一些知识点 学习使用

# ZSH

利用Oh My Zsh

 [github地址](https://github.com/robbyrussell/oh-my-zsh)

安装curl或wget

```shell
via curl
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
via wget
sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
```

配置

[终极 Shell——ZSH](https://zhuanlan.zhihu.com/p/19556676)

*可以设置主题 插件 强大的要命*

![](http://7xuxck.com1.z0.glb.clouddn.com/zsh.png)

# 配色

下载对应配色文件自己用的是Cobalt Neon

[下载地址](http://iterm2colorschemes.com)

- 执行 CMD+i


- 选择 Colors tab


- 执行 Import


-  在scheme文件夹中导入

![](http://7xuxck.com1.z0.glb.clouddn.com/coloeItem.png)

# 简单操作

## 选中

- 在 iTerm 中，双击选中，三击选中整行，四击智能选中(可自行配制)


- 在 iTerm 中，选中即被复制。都被放倒了剪贴板中

- 配合paste 在剪贴板中的效果很赞

  ![](http://7xuxck.com1.z0.glb.clouddn.com/paste.png)

  ​

## 屏幕分隔

- command+d：垂直


- command+shift+d：水平

![](http://7xuxck.com1.z0.glb.clouddn.com/Snip20160601_9.png)



## 重复路径

在新Tab中自动使用前Tab路径 如图所示：也可以加入一段文字自动执行

![](http://7xuxck.com1.z0.glb.clouddn.com/Snip20160601_8.png)



## 自动完成

**输入打头几个字母，然后输入command+; iterm将自动列出之前输入过的类似命令。**

![](http://7xuxck.com1.z0.glb.clouddn.com/Snip20160601_7.png)

**输入command+shift+h，iterm2将自动列出剪切板的历史记录。如果需要将剪切板的历史记录保存到磁盘，在Preferences > General > Save copy/paste history to disk.中设置。**

![](http://7xuxck.com1.z0.glb.clouddn.com/Snip20160602_10.png)

## 矩形选中

**同时按住option键，可以以矩形选中，类似于vim中的ctrl v操作。**

![](http://7xuxck.com1.z0.glb.clouddn.com/Snip20160602_12.png)



# 常用快捷键

## 标签

- 新建标签：command + t
- 关闭标签：command + w
- 切换标签：command + 数字 command + 左右方向键
- 切换全屏：command + enter
- 查找支持正则：command + f (所查找的内容会被自动复制)

## 分屏

- 垂直分屏：command + d
- 水平分屏：command + shift + d
- 切换屏幕：command + option + 方向键 command + [ 或 command + ]
- 查看历史命令：command + ;
- 查看剪贴板历史：command + shift + h
- 清屏：command + r =clear，
- 高亮当前鼠标的位置： ⌘+/ (标签页窗口太多，有时候会找不到当前的鼠标，找到它。 

## 其他

- 清除当前行：ctrl + u


- 到行首：ctrl + a
- 到行尾：ctrl + e
- 上一条命令：ctrl + p
- 搜索命令历史：ctrl + r
- 删除当前光标的字符：ctrl + d
- 删除光标之前的字符：ctrl + h
- 删除光标之前的单词：ctrl + w
- 删除到文本末尾：ctrl + k
- 交换光标处文本：ctrl + t

## 按住⌘键:

- 可以拖拽选中的字符串；


- 点击 url：调用默认浏览器访问该网址；


- 点击文件：调用默认程序打开文件；


- 点击文件夹：在 finder 中打开该文件夹；


- 同时按住option键，可以以矩形选中，类似于vim中的ctrl v操作。



