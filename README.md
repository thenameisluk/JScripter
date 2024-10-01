## Disclaimer

look i just wanted something like https://github.com/david-swift/Scripter/

but for javascript so i forked it and patched it

for the logo and all code credits to them

<p align="center">
  <img width="256" alt="Scripter Icon" src="data/icons/io.github.david_swift.Scripter.svg">
  <h1 align="center">JScripter</h1>
</p>

A very simple, native GNOME app for writing and executing simple JavaSript scripts.
It can be used as an advanced calculator or as an editor for testing simple scripts in JavaScript.

## Table of Contents

- [Disclaimer](#disclaimer)
- [Table of Contents](#table-of-contents)
- [Installation for debian](#installation-for-debian)
- [Usage](#usage)
- [Thanks](#thanks)
  - [Dependencies](#dependencies)

## Installation for debian

get latest swift from https://www.swift.org/install/linux/debian/12/#latest

install other deps
```
sudo apt install libgtksourceview-5-dev libadwaita-1-dev
```

fixup the PATH
```
export PATH=$PATH:/path/to/swift/bin/dir/
```

run make_deb

## Usage

Write a simple Javascript script. Run using the `Run` button or `Ctrl+Return`.
Print results using the `print` function so that they appear in the app's UI.

Look up and copy previous outputs in the sidebar. Open it using the button in the toolbar.

## Thanks

### Dependencies
- [Adwaita](https://github.com/AparokshaUI/Adwaita) licensed under the [MIT License](https://github.com/AparokshaUI/Adwaita/blob/main/LICENSE.md)
- [CodeEditor](https://github.com/AparokshaUI/CodeEditor) licensed under the [MIT License](https://github.com/AparokshaUI/CodeEditor/blob/main/LICENSE.md)
