# Installation
go into
```bash
cd ~/.local/share/gnome-shell/extensions/
```
then download
```bash
git clone https://github.com/OverLey42/floating-panel
```
add this to youre gnome-shell css
```bash
cd ~/.themes/YoureCustomShellTheme/gnome-shell/gnome-shell.css
```
```css
/* floating panel */
#panel.floating {
  background-color: #1a1c18;
  height: 38px;
  font-size: 14px;
}

#panel:floating {
  background-color: transparent;
  height: 38px;
  font-size: 14px;
}
```

after that log out or reastart gnome-shell


# Floating Panel

#### This project is a fork from https://github.com/Aylur/gnome-shell-extension-floating-panel/tree/main

#### Thank you @Aylur for this amazing gnome extension





    Note from Aylur:
    I purposefully didn't write customization for this extnsion,
    because I recommend and encourage to write your own theme.

    While making your theme, here is a quick guide:

    #panel.floating is the panel selector the nonfloating panel
        when the extension is available makes it easier to
        write 2 seperate styles, when the extension is
        enabled and when it is not.

    #panel:floating is the panel selector for when it is floating.

    if you want your floating style to apply on overview:
        apply the same styleshet to #panel:floating and #panel:overview

    IMPORTANT!
        make sure the nonfloating and the floating styles both have
        the same allocated space, becuase it can and will crash your
        shell if they don't.

    You should delete this stylesheet.css when you write your theme.
    Anything written here will overwrite any theme applied through
        gnome-tweaks.

```css
/* floating panel */
#panel.floating {
  background-color: #1a1c18;
  height: 38px;
  font-size: 14px;
}

#panel:floating {
  background-color: transparent;
  height: 38px;
  font-size: 14px;
}
```
