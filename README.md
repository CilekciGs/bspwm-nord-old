# BSPWM Nord

![alt text](https://github.com/CilekciGs/bspwm-nord/blob/main/Screenshot.png)

## Software Used

##### Terminal            : kitty
##### Program Launcher    : rofi
##### Bottom Bar	        : polybar
##### Web Browser	        : brave
##### File Manager	      : nautilus
##### Window Manager	    : bspwm
##### Hotkeys             : sxhkd 
##### Backlight Control   : xorg-xbacklight
##### Sound Backend	      : pulseaudio
##### Sound Control	      : pactl 
##### Networking Backend  : networkmanager
##### Networking Frontend : nm-applet
##### Notifications	      : dunst
##### Polkit		          : lxsession
##### Compositor	        : picom-ibhawgan
##### Wallpaper	          : feh
##### wmname		          : wmname (Q: What is wmname? A: It changes your wmname which fixes java ui)

### Please Don't blindly install everything listed here 
### It's Pretty simple to edit the configs
### For Custom Hotkeys edit ~/.config/sxhkd/sxhkdrc
### For Custom Startup Programs and Window Manager edit ~/.config/bspwm/bspwmrc

## Installation
### Move all the files to your home directory
```cp -r ./bspwm-nord/* ~/```
### Rename config to .config (had to upload like that because of github)
```mv ~/config/ ~/.config/```
### Make bspwmrc executable
```chmod +x ~/.config/bspwm/bspwmrc```

