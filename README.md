# Requirements
Supported WMs

|WM|Debian|Arch|Fedora|Gentoo|Void|
|-|-|-|-|-|-|
|i3-gaps|-*|i3-gaps|-*|i3-gaps|i3-gaps|
|bspwm|bspwm|bspwm|bspwm|bspwm|bspwm|

\* Must be built from source

**Programs**

|Program|Debian/Ubuntu|Arch|Fedora|Gentoo|Void|Explanation|
|-|-|-|-|-|-|-|
|Compton<sup>4</sup>|compton|- (replaced by Picom)|compton|compton|- (replaced by Picom)|Compositor for shadow & fading|
|Picom<sup>4</sup>|-<sup>1</sup>|picom|picom|picom|picom|Compositor for shadow & fading|
|Dunst|dunst|dunst|dunst|dunst|dunst|Notification daemon (for displaying notifications)
|hsetroot|hsetroot|hsetroot|-<sup>1</sup>|hsetroot|polybar|Set workspace background color|
|Polybar|-<sup>1</sup>/PPA (https://launchpad.net/~kgilmer/+archive/ubuntu/speed-ricer)<sup>5</sup>|polybar<sup>2</sup>|-<sup>1</sup>|polybar|polybar|Bar|
|Rofi|rofi|rofi|rofi|rofi|rofi|Launcher|
|xrdb|x11-xserver-utils|xorg-xrdb|xorg-x11-server-utils|xrdb|xrdb|For loading .Xresources|
|xautolock|xautolock|xautolock|xautolock|xautolock|xautolock|For auto locking|
|playerctl|playerctl|playerctl|playerctl|playerctl|playerctl|MPRIS (music) support|
|i3lock-color|-<sup>1</sup>|i3lock-color|-<sup>1</sup>|i3lock-color<sup>3</sup>|i3lock-color|Lockscreen|
|scrot|scrot|scrot|scrot|scrot|scrot|For taking screenshot for the lockscreen|
|ImageMagick|imagemagick|imagemagick|ImageMagick|imagemagick|ImageMagick|For blurring the screenshot for the lockscreen|
|oomox|deb (https://github.com/themix-project/oomox/releases)|oomox<sup>2</sup>|-<sup>1</sup>|-<sup>1</sup>|-<sup>1</sup>|Generate a GTK theme to match the color scheme|

<sup>1</sup> Must be built from the source\
<sup>2</sup>Package available on AUR\
<sup>3</sup> Search on https://gpo.zugaina.org/ to find overlay that have the package\
<sup>4</sup> Install only one of both\
<sup>5</sup> PPA only available for Ubuntu / deriveratives

**Fonts**

Icon Font

|Font|Debian|Arch|Fedora|Gentoo|Void|
|-|-|-|-|-|-|
|Font Awesome 5|-*|ttf-font-awesome|-*|fontawesome|font-awesome5|

Default Fonts

|Font|Debian|Arch|Fedora|Gentoo|Void|
|-|-|-|-|-|-|
|Roboto|fonts-roboto|ttf-roboto|google-roboto-fonts|roboto|fonts-roboto-ttf|
|Noto Sans CJK|fonts-noto-cjk|noto-fonts-cjk|google-noto-sans-cjk-*-fonts|noto-cjk|noto-fonts-cjk|
|Source Code Pro|-*/PPA (https://launchpad.net/~kgilmer/+archive/ubuntu/regolith-stable)<sup>2</sup>|adobe-source-code-pro-fonts|adobe-source-code-pro-fonts|source-pro|font-adobe-source-code-pro|

<sup>1</sup> Must be downloaded and copied to font directory/
<sup>2</sup> PPA only available for Ubuntu / deriveratives

# Installation
Copy .minoflat directory, .Xresources and .Xresources.d directory to your home directory (~) and some configurations in .config to ~/.config or you can copy all files in this directory to your home directory

# User scripts
edit ~/.minoflatrc or put a shell script in ~/.minoflatrc.d/ for user scripts

# Preview
<img src="screenshots/2019-10-20-11.png">\
Programs: qutebrowser, st, neofetch & cmus\
WM: i3-gaps
<img src="screenshots/2019-11-06-03.png">
Program: GIMP\
WM: bspwm
<img src="screenshots/lock.png">
Lockscreen


# Scripts

```~/.minoflat/scripts/tiling-common``` init script for i3 & bspwm and as a workaround for passing .Xresources value to hsetroot\
```convert_xresources``` To convert .Xresources to Minoflat's format (see convert_xresources -h for information)

# Credits
Default color scheme: Relaxed by Michael Kühnel https://github.com/Relaxed-Theme/relaxed-terminal-themes \
Picture edited with GIMP by Kristin Hardwick https://stocksnap.io/photo/ACSH8DMZYC
