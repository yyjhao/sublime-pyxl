sublime-pyxl
============

[pyxl](https://github.com/dropbox/pyxl) syntax highlighting for Sublime Text.

## Installation

### Package Control

Make sure you already have Package Control installed. Choose Install Package
from the Command Palette Select sublime-pyxl and press Enter

### Manual installation

Download the files using the GitHub.zip download option Unzip the files to your
Sublime Text Packages directory.

## Usage

After installing, set the syntax to `Python (pyxl)`.

## SublimeLinter

If you want to be able to lint the files with this syntax properly, go to
Preferences - Package Settings - SublimeLinter - Settings (User) and add the
following mapping to the `syntax_map`:

```json
    "syntax_map": {
        ...
        "python (pyxl)": "python",
        ...
    }
```