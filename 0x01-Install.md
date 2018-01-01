# 安装

# 1. 安装Command Line Developer Tools

如果你安装了Xcode并打开使用过，或者你很明白git、curl这些命令行工具已经安装了，那可以跳过这一步。

如果没有安装过，那可以打开Terminal.app 然后输入git回车，系统检测到没有安装Command Line Developer Tools，会提示安装，如下图：

![](media/15148180217989.jpg)

点击Install，然后Agree就可以了。

# 2. 安装MacVim

MacVim下载地址 https://github.com/macvim-dev/macvim/releases/ ，双击MacVim.dmg后把MacVim.app拖到/Applications目录。

![](media/15148183321072.jpg)

![](media/15148189232636.jpg)



# 3. 清理当前vim配置

打开Terminal.app

```
rm -rf ~/.vim
rm ~/.vim*
```
（每行表示一次回车）

# 4. 安装SpaceVim

打开Terminal.app

```
curl -sLf https://spacevim.org/install.sh | bash
```

![](media/15148185878500.jpg)

完成后运行MacVim.app

![](media/15148189781244.jpg)

首次打开会提示选择一个模式，按键盘”1“选择第一个模式。然后，VIM会安装很多插件，等待安装完成。

![](media/15148190874254.jpg)



