# Godot Animation Resetter

<img src="icon.png?raw=true"  align="right" />

[![MIT license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![English README](https://img.shields.io/badge/README-English-red)](README.md)

这个插件会在“动画”底部面板的“动画”菜单中添加“从 RESET 补全轨道”选项。该选项会根据 RESET 动画中的轨道添加缺失的轨道。

> [!TIP]
> 从 Godot 4.2 开始就没有必要使用这个插件了。启用 `AnimationPlayer` 的 `deterministic` 属性即可使用 RESET 动画作为回退值。

## 安装

这是一个普通的 Godot 插件。安装时，先下载 ZIP 包，解压后将 `addons/` 文件夹移动到你的项目文件夹中，然后在项目设置中启用本插件。

## 使用

启用该插件后，你会在“动画”底部面板的“动画”菜单中看到“从 RESET 补全轨道”选项。当前选中的 `AnimationPlayer` 包含 `RESET` 动画时，该选项可用。

<p align="center">
  <img src="screenshots/menu-zh_CN.png?raw=true" />
</p>

选择这个菜单项后，会在执行操作前让你确认各个动画要添加的轨道。该操作可撤销。

<p align="center">
  <img src="screenshots/prompt-zh_CN.png?raw=true" />
</p>
