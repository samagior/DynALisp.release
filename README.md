# DynALisp

DynALisp is an AutoCAD plugin and development platform written in AutoLISP / Visual LISP: about 40 DynALisp tools (drawing presets, layers, cleaning, output prep, setup...) and over 100 tools by Lee Mac, each with its docs page, and one window for every setting.

This repository holds the **releases** of DynALisp: the setup and the changes of each version.

## Download

**[Download the latest version](https://github.com/samagior/DynALisp.release/releases/latest)**: `DynALisp-Setup-<version>.exe`.

## Requirements

AutoCAD 2010 (R18) or later, on Windows. AutoCAD LT has no AutoLISP and can't run DynALisp.

## Install

1. Run `DynALisp-Setup-<version>.exe`. It installs for your Windows user only (no admin rights), into `%APPDATA%\Autodesk\ApplicationPlugins\DynALisp.bundle`. Close AutoCAD first, or the setup waits for you to.
2. Start AutoCAD. Accept the security prompt if AutoCAD asks to load DynALisp. Type `Dyl-Info` for help.

Windows may warn about an unknown publisher (the setup is not signed yet): click **More info**, then **Run anyway**.

If you have settings saved from another installation, pick their `DynALisp-Settings.txt` on the **Import Saved Settings** page of the setup.

## Updates

`Dyl-Info` tells you when a new version is out: **Update to...** shows what changed and installs it when you close AutoCAD. To install updates without asking, turn on **Install updates automatically** in `Dyl-Settings` (checked once a day). After an update, AutoCAD shows the changes once. Each release lists its changes, and its `CHANGELOG.md` has those of every version.

## Uninstall

Uninstall DynALisp from Windows Settings > Apps. It first offers to save your settings (your edited files, the `Dyl-Settings` options and your own tools) in a folder you choose, then removes everything DynALisp added. To move your settings without uninstalling, use **Export settings** / **Import settings** in `Dyl-UserFiles`.

## Problems And Ideas

Open an [issue](https://github.com/samagior/DynALisp.release/issues): say what you did, what happened, and your versions of DynALisp (`Dyl-Info`) and AutoCAD.

## Licence

DynALisp is released under the [GNU GPL v3](LICENSE); the setup holds its source code (the Lisp files). The Lee Mac tools keep their own licence, included in the setup.
