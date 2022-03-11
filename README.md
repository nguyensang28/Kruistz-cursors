# Kruistz cursors
This is an X11 Cursor theme inspired from [Graphite gtk theme](https://github.com/vinceliuice/Graphite-gtk-theme)

## Installation
To install the cursor theme simply copy the compiled theme to your icons
directory. For local user installation:

```
./install.sh
```

For system-wide installation for all users:

```
sudo ./install.sh
```

Then set the theme with your preferred desktop tools.

## Building from source
You'll find everything you need to build and modify this cursor set in
the `src/` directory. To build the xcursor theme from the SVG source
run:

```
./build.sh
```

This will generate the pixmaps and appropriate aliases.
The freshly compiled cursor theme will be located in `dist/`

## Preview
![normal](preview-normal.png)
![nord](preview-nord.png)
