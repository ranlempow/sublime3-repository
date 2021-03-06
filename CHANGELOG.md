## RansTool [1.5.2] - 2019-10-03
- fixed: bug on install_font.py
- fixed: use fix_markdown_editing_enter_glitch on macos only

## RansTool [1.5.1] - 2019-09-19
- remove ChineseLocalizations package, this package is not well maintained
- auto install extra package on `~/.config/sublime-life/extra-packages.ini`
- fixed: markdown color_scheme is correct now
- add install.sh to help user install RansTool
  call with ST_PACKAGE_PATH to set sublime package path

## RansTool [1.5.0] - 2019-09-19
- add command FixMarkdwonEditingEnterGlitchCommand
- add many bundle package:
  `AdvancedNewFile`, `AlignTab`, `All Autocomplete`,
  `ChineseLocalizations`, `FileDiffs`, `HexViewer`,
  `Line Endings Unify`, `Outline`, `PlainTasks`, `RawLineEdit`,
  `SideBarEnhancements`, `StringEncode`, `SyncedSideBar`,
  `SyntaxManager`, `TrailingSpaces`, `Trimmer`
- fixed: right click menu on sidebar
- hack: redundant prompt at encode detecting on ConvertToUTF8

## RansTool [1.4.1] - 2019-03-21
- sublime text 3.2 released
- remove package GitGutter
- choose_font: add hack font
- choose_font: new ./lib/install_font
- set default fontface to `hack font nerd`
- change theme to `Theme - Monokai Pro`
- change sublimelinter theme to `Theme - Monokai Pro`
- use `SublimeLinter-addon-toggler` and key binds with `f10`
- TODO: sublimelinter need enve to install linter binary executables
- deprecated: ./gitgutter_switch.py
- deprecated: ./linter_switch.py

## RansTool [1.4.0] - 2019-03-20
- recompose project reposity structure, again
- remove package Extra Completion (ranlempow)
- remove package SublimeLinter-CleanCode (ranlempow)
- change package Open Anything (ranlempow) to noahcoad/open-url
- change package RansTool (ranlempow) to ranlempow/Sublime-Life#master
- setting: no fold buttons on line number bar
- setting: default font_size to 16px
- setting: show full path at title
- setting: sidebar icon are atomized and mono
- hotkey: ctrl+u to delete before cursor
- utf-8 support on macos/linux: add package Codecs33, ConvertToUTF8
- add language package: INI

## SublimeLife [1.3.5] - 2017-12-12
- recompose project reposity structure
- keep everything in signle reposity

## RansTool [1.3.4] - 2017-02-08
- change: default setting to A File Icon
- change: default setting to theme
- change: default setting SublimeLinter

## RansTool [1.3.2] - 2017-02-07
- added package: A File Icon

## RansTool [1.3.1] - 2017-02-07
- new self-update system

## RansTool [1.3.0] - 2017-02-07
- no longer ignore default markdown package
- override Markdown GFM default setting
- added: added: new command choose font
- changed hotkey to ctrl+alt+?

## CleanCode [1.0.1] - 2017-02-05
- fixed: inline noqa is no longer regard as global
- added: inline noqa support not only pep8-linter

## Open Anything [1.1.1] - 2017-02-05
- changed hotkey to ctrl+alt+?
- added: ctrl+alt+d to integrate dev-sh

## Ancient [1.0.1] - 2017-02-07
- added: support diff syntax
- added: support find-in-file syntax
- added: more markdown syntax