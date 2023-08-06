
# evo cursor

Evo cursor is animated cursor for Linux. This repository files are use to build evo cursor.![App Screenshot](https://raw.githubusercontent.com/notyz77/evo_cursor/main/Image.png)


## Installation

To download evo cursor [Link](https://github.com/notyz77/evo_cursor/releases).

For system-wide installation:
```bash
  tar -zxvf evo_cursor.tar.gz
  sudo mv evo_cursor/ /usr/share/icons/
```

For local installation:
```bash
  mkdir -p $HOME/.icons/ && tar -zxvf evo_cursor.tar.gz -C $HOME/.icons/
```
# Set the cursor theme
There are various way to set this (or another) cursor theme.

You will find all the needed informations on this [ArchWiki](https://wiki.archlinux.org/title/Cursor_themes#GNOME).

# Uninstallation

If you installed it locally, run this command in your terminal:
```bash
  rm -r $HOME/.icons/evo_cursor/
```

And if you installed it system-wide use:
```bash
  sudo rm -r /usr/share/icons/evo_cursor/
```

Note: It is recommended to install the cursor theme system-wide because some programs are unable to get the cursor theme as a local install, like Lightdm.