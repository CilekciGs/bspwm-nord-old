# BSPWM Nord

![alt text](https://github.com/CilekciGs/bspwm-nord/blob/main/Screenshot.png)

## Software Used

##### Terminal            : kitty
##### Program Launcher    : rofi
##### Top Bar	        : polybar
##### Web Browser	        : brave
##### File Manager	      : pcmanfm
##### Window Manager	    : bspwm
##### Hotkeys             : sxhkd 
##### Backlight Control   : xorg-xbacklight
##### Sound Backend	      : pulseaudio
##### Sound Control	      : pactl 
##### Networking Backend  : networkmanager
##### Notifications	      : dunst
##### Polkit		          : lxsession
##### Compositor	        : picom
##### Wallpaper	          : feh
##### Theme               : Nordic-dark
##### Icons               : kora

### Please Don't blindly install everything listed here 
### It's Pretty simple to edit the configs
### For Custom Hotkeys edit ~/.config/sxhkd/sxhkdrc
### For Custom Startup Programs and Window Manager edit ~/.config/bspwm/bspwmrc

## Fonts
#### Siji-ng
#### Noto_Sans
#### Feather
#### Iosevka-Nerd-Font
#### Hurmit-Nerd-Font-Mono
#### Fantasque-Sans-Mono-Nerd-Font

## Installation
### Move all the files to your home directory
```cp -r ./bspwm-nord/* ~/```
### Rename config to .config (had to upload like that because of github)
```mv ~/config/ ~/.config/```
### Make bspwmrc executable
```chmod +x ~/.config/bspwm/bspwmrc```
### Make Rofi scripts executeable
```chmod +x ~/.config/rofi/PowerMenu/powermenu.sh && chmod +x ~/.config/rofi/Launcher/launcher.sh```

