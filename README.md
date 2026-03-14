# KSV2VS

KSV2VS is a VScode extension adding KaravaiSV syntax highlightning.

## About

This extension adds KaravaiSV syntax highlightning to `.ksv` files.

It uses grammar injection mechanism which drastically reduces highlight messes.

## Dependencies

As KaravaiSV as a templating tool for **SystemVerilog** via **Python** instruments, this extension requires to install the following SystemVerilog and Python standalone syntax highlightning extensions.

* [SystemVerilog extension by Masahiro Hiramori](https://vscode.dev/github/BIG-Denis/raspberry-core/blob/dev_migration)
* [Python extension by Microsoft](https://vscode.dev/github/BIG-Denis/raspberry-core/blob/dev_migration)

## Highlightning

All the highlightning stays the same for SystemVerilog and Python languages itself.

However, the KaravaiSV-specific keywords been granted with their own highlights.

* `<$` and `$>` has got the yellow color in default theme
* `</` and `/>` has got the dark blue color in default theme

Specified colors are taken from default VScode name scope, which guarantees their portability between global color themes.

## Installation

### Raw sources

1. Download raw sources from [GitHub](https://github.com/BIG-Denis/ksv2vs).
2. Extract and move all the repo's content in any folder.
3. In VScode press `F1` and type `>Developer: Install Extension from Location...`
4. Choose folder where extracted extension source code are stored.

> It is recommended to download source code from latest release for maximum stability.

### VSIX

Currently no VSIX file are provided, but there are plans to do that.

### VScode marketplace

Currently this extension is not published at VScode marketplace, but there are plans to do that.

## Additional information

This extension is in development. New features and bug fixes will be released as needed.

If you found any issues please report them via [GitHub create an issue page](https://github.com/BIG-Denis/ksv2vs/issues).
