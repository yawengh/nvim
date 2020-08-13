# My Neovim Configuration

[中文版](./README_cn.md)

This repository has my personal NeoVim configuration files. (I'm a [colemak](https://www.colemak.com) user.)

If you not understand this NeoVim configuration, please don't use it, Otherwise you may have some problems.

![](./screenshots/1.png)

## Guide

<!-- TOC GFM -->

* [Before using](#before-using)
	- [To check the "health"](#to-check-the-health)
	- [For Python Debugger (via `vimspector`)](#for-python-debugger-via-vimspector)
	- [Config `Python` path](#config-python-path)
	- [For Taglist:](#for-taglist)
	- [For FZF](#for-fzf)
	- [And also...](#and-also)
* [Key mappings](#key-mappings)
	- [Movements](#movements)
	- [Other keys](#other-keys)
* [Other related projects](#other-related-projects)

<!-- /TOC -->

## Before using

- [ ] Install `pynvim` (pip)
- [ ] Install `nodejs`, and do `npm install -g neovim`
- [ ] Install nerd-fonts (actually it's optional but it looks real good)

### To check the "health"

You can run `:checkhealth` in vim to check if your NeoVim work well.

### For Python Debugger (via `vimspector`)
- [ ] Install `debugpy` (`pip`)

### Config `Python` path
- [ ] Well, make sure you have python
- [ ] See `_machine_specific.vim`

### For Taglist:
- [ ] Install `ctags` for function/class/variable list

### For FZF
- [ ] Install `fzf`
- [ ] Install `ag` (`the_silver_searcher`)

### And also...
- [ ] Install `figlet` for inputing text ASCII art
- [ ] Install `xclip` for system clipboard access (`Linux` and `xorg` only)

## Key mappings

### Movements

Up, down, left, right to use:

```
    ^
    u
< n   i >
    e
    V
```

Move cursor 5 times to use:

```
    ^
    U
< N   I >
    E
    V
```
Info: the `N` and `I` are move cursor to line the first and the end.

### Other keys

| Keys | Features                                    |
|------|---------------------------------------------|
| k    | Insert                                      |
| K    | Insert to the line beginning                |
| l    | Undo                                        |
| L    | Undotree (a plugin)                         |
| b    | Move cursor to previous word's beginning    |
| B    | Move cursor to previous 5 words's beginning |
| w    | Move cursor to next word's beginning        |
| W    | Move cursor to next 5 words's beginning     |
| h    | Move cursor to next word's end              |
| tt   | Open the file explorer (coc.nvim)           |
| ts   | Translate the word at the cursor (coc.nvim) |
| S    | Save the file in a buffer                   |
| Q    | Quit vim or a tab (all buffer are saved)    |

## Other related projects

- [dwm](https://github.com/KiteAB/dwm)
- [st](https://github.com/KiteAB/st)
- [scripts](https://github.com/KiteAB/scripts)
- [.config](https://github.com/KiteAB/.config)
