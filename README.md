<h1 align="center">Menu with script</h1>

<p align="center">Custom menu using rofi and script bash</p>

![bash](https://img.shields.io/static/v1?style=for-the-badge&message=bash&color=green&logo=GNU%20Bash)&nbsp;

# Install
```
$ git clone https://github.com/gabriel45959/script_menu.git
```
```
$ sudo ln -s ~/script_menu/menu /usr/bin/menu
```

# Key Bindings
Using sxhkd, change .config/qtile/sxhkd/sxhkdrc

```
# App
super + F1
        menu app_tools

# Edit config
super + F2
        menu edit_config

# Tools
super + F3
        menu file_tools

# Web Bookmarks
super + F4
        menu web_bookmark

# Apps running on window
super + F5
    rofi -width 50 -lines 7 -i -bw 0 -show window
```
Reload sxhkd: super + shift + s
