# Internet Player

![Linux Mint](https://img.shields.io/badge/Linux%20Mint-22.2-76b900?style=flat-square&logo=linux&logoColor=white)
![Vala](https://img.shields.io/badge/Vala-GTK3-6B4FBB?style=flat-square)
![GStreamer](https://img.shields.io/badge/GStreamer-1.0-FF6B00?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)
![Built with Grok](https://img.shields.io/badge/Built%20with-Grok-000000?style=flat-square&logo=x&logoColor=white)  

*Internet Stream Player - Variants 1 and 2*  

![Internet Player](Internet%20Player.png)  



*EQ Internet Stream Player - Variants 3-4-5*

![EQ Internet Player](EQ%20Internet%20Player.png)  

A simple internet radio / stream player for **Linux Mint 22.2**.

Written in Vala + GTK3 + GStreamer. Lightweight, dark interface, with support for adding custom stations.

## Installation  

All ready-to-install files are in the zip archive  `stream radio.zip`  in the **Good Variants** folder.

Download `radio-player_1.0.*_amd64.deb` and install it:

```bash
sudo dpkg -i radio-player_1.0.*_amd64.deb
sudo apt install -f
```

The second command installs any missing dependencies.  

Note: Versions can be from 1 to 5.  
Replace the * with the number of the .deb file you want to install (e.g. radio-player_1.0.3_amd64.deb).

### Required packages

The application depends on:

- `libgtk-3-0`
- `gstreamer1.0-plugins-base`
- `gstreamer1.0-plugins-good`
- `gstreamer1.0-plugins-bad`
- `gstreamer1.0-libav`
- `gstreamer1.0-pulseaudio`

On Linux Mint 22.2 these are usually pulled in automatically by `sudo apt install -f`.

You can also install them manually beforehand:

```bash
sudo apt install libgtk-3-0 gstreamer1.0-plugins-base gstreamer1.0-plugins-good gstreamer1.0-plugins-bad gstreamer1.0-libav gstreamer1.0-pulseaudio
```

## Features

- Station selection from a list
- Play / Pause / Stop
- Volume control
- Add custom streams ( **+** button)
- Remove custom streams ( **−** button)
- Custom stations are saved between restarts

## Uninstall

```bash
sudo apt remove radio-player
```
