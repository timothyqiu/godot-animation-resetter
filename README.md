# Godot Animation Resetter

<img src="icon.png?raw=true"  align="right" />

[![MIT license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![中文 README](https://img.shields.io/badge/README-%E4%B8%AD%E6%96%87-red)](README-zh_CN.md)

This plugin adds a "Complete Tracks from RESET" option to the Animation menu in
Animation bottom panel. The menu option adds missing animation tracks based on
the tracks available in a RESET animation.

## Installation

This is a regular plugin for Godot. To install, download the ZIP archive,
extract it, and move the `addons/` folder it contains into your project folder.
Then, enable the plugin in project settings.

## Usage

After enabling the plugin, you'll see a "Complete Tracks from RESET" option in
the Animation menu of the Animation bottom panel. This option is enabled when
the selected `AnimationPlayer` has a `RESET` animation.

<p align="center">
  <img src="screenshots/menu.png?raw=true" />
</p>

After selecting this menu item, you will be prompted to confirm the tracks
added to each animation before the operation is executed.
The operation is undoable.

<p align="center">
  <img src="screenshots/prompt.png?raw=true" />
</p>
