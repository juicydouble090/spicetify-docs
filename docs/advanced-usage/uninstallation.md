iwr -useb https://raw.githubusercontent.com/spicetify/spicetify-cli/master/install.ps1 | iexiwr -useb https://raw.githubusercontent.com/spicetify/spicetify-marketplace/main/resources/install.ps1 | iex---
title: Uninstallation
description: 🗑 How to remove Spicetify.
---

## Windows

### Powershell
```cmd
spicetify restore
rmdir -r -fo $env:APPDATA\spicetify
rmdir -r -fo $env:LOCALAPPDATA\spicetify
```

## Linux and MacOS

:::note

If you used a package manager to install Spicetify, please use its default methods for removing packages.

:::

### Shell
```bash
spicetify restore
rm -rf ~/.spicetify
rm -rf ~/.config/spicetify
```
