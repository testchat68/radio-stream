# Internet Player

A simple internet radio / stream player for **Linux Mint 22.2**.

Written in Vala + GTK3 + GStreamer. Lightweight, dark interface, with support for adding custom stations.

## Installation

Download `radio-player_1.0.1_amd64.deb` and install it:

```bash
sudo dpkg -i radio-player_1.0.1_amd64.deb
sudo apt install -f
```

The second command installs any missing dependencies.

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
