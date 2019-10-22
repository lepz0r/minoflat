# Requirements
Supported WMs
|WM|Ubuntu|Arch Linux|Explanation|
|-|-|-|-|
|i3-gaps|-*|i3-gaps|Window manager (WM)|
|bspwm|bspwm|bspwm|Window manager (WM)|
\* Must be build from source

|Program|Ubuntu|Arch Linux|Explanation|
|-|-|-|-|
|Compton|compton|compton|Compositor for shadow & fading|
|Dunst|dunst|dunst|Notification daemon (for displaying notifications)
|hsetroot|hsetroot|hsetroot|Set workspace background color|
|Polybar|-*|polybar**|Bar|
|Rofi (launcher, you can set your launcher in .config/i3/config for i3-gaps)|rofi|rofi|Launcher|
|xrdb|x11-xserver-utils|xorg-xrdb|For loading .Xresources|

\* Must be build from source\
\*\* Package available on AUR

**Fonts**

Icon Font

|Font|Ubuntu|Arch Linux|
|-|-|-|
|Font Awesome 5|fonts-font-awesome|ttf-font-awesome

Default Fonts

|Font|Ubuntu|Arch Linux|
|-|-|-|
|Roboto|fonts-roboto|ttf-roboto
|Noto Sans CJK|fonts-noto-cjk|noto-fonts-cjk
|Source Code Pro|-*|adobe-source-code-pro-fonts

\* Must be downloaded and copied to font directory

**Optional**

scrot (for screenshots)

# Installation
Copy .minoflat directory, .Xresources to your home directory (~) and some configurations in .config to ~/.config

# Preview
<img src="screenshots/2019-10-20-11.png">\
Programs: qutebrowser, st, neofetch & cmus

<img src="screenshots/2019-10-20-11_000.png">
Programs: st & neofetch

# Credits
Default color scheme: Relaxed by Michael Kühnel https://github.com/Relaxed-Theme/relaxed-terminal-themes
