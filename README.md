# Changes made to build for Raspberry Pi 4 XFCE4 Panel
- meson.build: Changed version check for libxfce4panel-2.0
- volumebutton.vala: removed line 90
- volumepopup.vala: edited to set horizontal

# xfce4-alsa-plugin
Simple ALSA volume control for xfce4-panel

## Installation
### Dependencies
- Vala
- Meson >= 0.37.0
- ALSA userspace library (libasound)
- gettext >= 0.19.7
- libxfce4panel-2.0 >= 4.13.0
- gtk+-3.0 >= 3.20.0

### Building
```sh
# meson build -Dgtk3=true
meson build
ninja -C build
ninja -C build install
```
