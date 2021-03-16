
# Chameleon LeftWM Configuration

This is the config files for the chameleon theme for LeftWM

Note that my up and down scripts are written for the **fish** shell. Without fish they won't work.

```
DE		: Nixos
WM		: LeftWm
bar		: Polybar
launcher	: Rofi
```

# Dependencies

- [LeftWM] (https://github.com/leftwm/leftwm)
- [Polybar] (https://github.com/polybar/polybar)
- [Rofi] (https://github.com/davatorium/rofi)
- [Fish shell] (https://github.com/fish-shell/fish-shell)

# Installation

1. Install all the required dependencies

2. Clone the repository
```BASH
git clone https://github.com/Chamelochite/chameleonLeftWm.git
```

3. Make a copy of the project in your themes folder
```BASH
cp -r ./chameleonLeftWm  ~/.config/leftwm/themes
```

4. Remove the symlink to your current theme if set

```BASH
rm ~/.config/leftwm/themes/current
```
5. Set this as your current theme

```BASH
ln -s ~/.config/leftwm/themes/chameleonLeftWm  ~/.config/leftwm/themes/current
```

6. Restart your window manager

```Default shortcut
$MOD + Shift + r
```
