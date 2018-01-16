# Sublime Text configuration

Personal key mappings, packages, snippets and preferences for [Sublime Text 3](http://www.sublimetext.com/).

![Open file in customised editor with expanded find panel](./screenshot.png)

> The typeface pictured is [Native](https://fortfoundry.com/products/native) by Fort Foundry. I previously used [Source Code Pro](https://fonts.google.com/specimen/Source+Code+Pro) which is a close substitute.

## Overview

I use Sublime as my primary editor on all manner of projects, but only commit stuff here when it becomes part of my long-term toolkit. Feel free to copy anything and adjust what you need for your own workflow.

**Theme**: [Boxy](https://packagecontrol.io/packages/Boxy%20Theme)  
**Colour scheme**: [gruvbox](https://github.com/morhetz/gruvbox)

#### Plugins

Plugin dependencies are listed in `Package Control.sublime-settings`. Individual plugin settings are largely defined in `.sublime-settings` files of matching name.

#### Preferences

Core editor settings, including theme options, are defined in `Preferences.sublime-settings`. Some options are conditionally overridden per-platform using [PlatformSettings](https://packagecontrol.io/packages/PlatformSettings).

Additional file type associations are set in separate `<syntax>.sublime-settings` files.

#### Key mappings

These are defined per-platform in each `Default (<platform>).sublime-keymap` file.

#### Build systems

Additional generic build systems are defined under `Build/`.

## Installation

Place contents under your local Sublime Text `Packages/User/` directory and restart Sublime. Alternatively, sync settings from a local folder using [Package Syncing](https://packagecontrol.io/packages/Package%20Syncing), which is awesome for maintaining the same configuration over multiple devices.
