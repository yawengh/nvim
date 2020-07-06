# 我的 NeoVim 配置文件

[English version](./README.md)

此仓库包含我的个人 NeoVim 配置文件 (我是一个 [colemak](https://www.colemak.com) 用户)

如果你不能读懂这份配置, 请不要使用他, 否则你很有可能会遇到问题

![](./screenshots/1.png)


## 攻略

- [使用之前](#使用之前)
- [键位](#键位)
- [其它相关项目](#其它相关项目)


## 使用之前

- [ ] 安装 `pynvim` (pip)
- [ ] 安装 `nodejs`, 然后在终端输入 `npm install -g neovim`
- [ ] 安装 nerd-fonts (这是可选的, 不过它看起来十分棒)

### 检查 "健康"

你可以在 vim 中运行 `:checkhealth` 来检测你的 NeoVim 是否正常运转

### Python 程序调试 (通过 `vimspector`)
- [ ] 安装 `debugpy` (`pip`)

### 配置 `Python` 路径
- [ ] 确保你安装了 Python
- [ ] 查看 `_machine_specific.vim` 文件并根据情况做出更改

### 标签列表:
- [ ] 安装 `ctags` 以供应函数 / 类 / 变量的列表

### FZF (模糊文件查找器)
- [ ] 安装 `fzf`
- [ ] 安装 `ag` (`the_silver_searcher` 的依赖)

### 其它项...
- [ ] 安装 `figlet` 以打印 ASCII 艺术字
- [ ] 安装 `xclip` 以让 Vim 获得读取系统剪切板的能力 (仅需在 `Linux` 与 `xorg` 环境下安装)


## 键位

### 移动方式

上下左右的移动可以使用:

```
    ^
    u
< n   i >
    e
    V
```

移动五格光标可以使用:

```
    ^
    U
< N   I >
    E
    V
```
提示: `N` 与 `I` 键分别为移动至行首或行尾

### 其它按键

| 按键 | 功能                             |
|------|----------------------------------|
| k    | 切换至插入模式                   |
| K    | 将光标移动至行首并切换至插入模式 |
| l    | 撤销                             |
| L    | Undotree (插件功能)              |

## 其它相关项目

- [dwm](https://github.com/KiteAB/dwm)
- [st](https://github.com/KiteAB/st)
- [scripts](https://github.com/KiteAB/scripts)
- [.config](https://github.com/KiteAB/.config)
