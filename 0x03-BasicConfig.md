# 简单配置


SpaceVim提供了我们可以自定义配置的文件，就是`~/.SpaceVim.d/init.vim`文件，所有自定义的内容都可以放到这个文件中。这个文件夹也就可以通过git管理起来。

以下配置可参考[我的配置文件](https://github.com/everettjf/.SpaceVim.d/blob/master/init.vim)


# 空格键延迟

默认按下空格键是1秒后显示选项，由于刚刚上手，可以设置的短一些，例如200毫秒

```
set timeoutlen=200
```

# 换个主题

所有支持的主题 https://github.com/rafi/awesome-vim-colorschemes

```
let g:spacevim_colorscheme = 'molokai'
```


# 语言支持

有些语言我用不到，注释掉吧。（这里根据个人情况来，我主要是用vim来写Python和Go）

![](media/15148300470000.jpg)


# 字体配置

如果仔细看，可能会发现安装后有些显示问号（？）的地方，这是因为还需要配置一些字体。

这里字体我们使用 https://github.com/ryanoasis/nerd-fonts

可以这样安装：

```
brew tap caskroom/fontsbrew cask install font-hack-nerd-font
```

对于MacVim，安装后在配置文件中加入：

```
let g:spacevim_guifont='Knack\ Nerd\ Font:h12'
```

Terminal.app需要单独配置字体：

![](media/15148306746160.jpg)


iTerm2.app也需要单独配置字体：

![](media/15148306197631.jpg)



# 总结

然后，就MacVim像我这样啦。

![](media/15148307475813.jpg)


