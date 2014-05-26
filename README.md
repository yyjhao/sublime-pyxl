sublime-pyxl
============

[pyxl](https://github.com/dropbox/pyxl) syntax highlighting for Sublime Text.

Inspired by [sublime-react](https://github.com/reactjs/sublime-react) and [PythonImproved](https://github.com/MattDMo/PythonImproved).

![Screenshot](http://i.imgur.com/SPqhWhc.png)

## Installation

### Package Control

1. Make sure you already have Package Control installed
2. Choose Install Package from the Command Palette
3. Select pyxl syntax and press Enter

### Manual installation

Download the files using the GitHub.zip download option Unzip the files to your
Sublime Text Packages directory.

## Usage

After installing, set the syntax to `Python (pyxl)` for the file with pyxl
syntax.

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