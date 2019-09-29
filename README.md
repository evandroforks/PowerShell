# PowerShell Package for Sublime Text 3

[![Join the chat at https://gitter.im/SublimeText/PowerShell](https://badges.gitter.im/SublimeText/PowerShell.svg)](https://gitter.im/SublimeText/PowerShell?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Adds support for the MS PowerShell programming language.


## Installation

### By Package Control

1. Download & Install **`Sublime Text 3`** (https://www.sublimetext.com/3)
1. Go to the menu **`Tools -> Install Package Control`**, then,
   wait few seconds until the installation finishes up
1. Go to the menu **`Tools -> Command Palette...
   (Ctrl+Shift+P)`**
1. Type **`Preferences:
   Package Control Settings – User`** on the opened quick panel and press <kbd>Enter</kbd>
1. Then,
   add the following setting to your **`Package Control.sublime-settings`** file, if it is not already there
   ```js
   [
       ...
       "channels":
       [
           "https://raw.githubusercontent.com/evandrocoan/StudioChannel/master/channel.json",
           "https://packagecontrol.io/channel_v3.json",
       ],
       ...
   ]
   ```
   * Note,
     the **`https://raw...`** line must to be added before the **`https://packagecontrol...`**,
     otherwise you will not install this forked version of the package,
     but the original available on the Package Control default channel **`https://packagecontrol...`**
1. Now,
   go to the menu **`Preferences -> Package Control`**
1. Type **`Install Package`** on the opened quick panel and press <kbd>Enter</kbd>
1. Then,
search for **`PowerShell`** and press <kbd>Enter</kbd>

See also:
1. [ITE - Integrated Toolset Environment](https://github.com/evandrocoan/ITE)
1. [Package control docs](https://packagecontrol.io/docs/usage) for details.


### Developing

You want to contribute? Awesome! Take a look at [CONTRIBUTING.md](CONTRIBUTING.md).

### EditorSyntax

Syntax highlighting is provided by the project [EditorSyntax][].
Issues about the grammar should be opened in **EditorSyntax** instead of this repo.

[package_control]: https://sublime.wbond.net/installation
[EditorSyntax]: https://github.com/PowerShell/EditorSyntax
