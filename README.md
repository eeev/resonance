# resonance
A clean, feature-rich Arch configuration
## preview

## requirements
The easy way is to install the latest EndeavourOS with bspwm as a window manager. This will also set up all components for usage comfort, such as audio control, networking, etc.<br/>
However, if you want to use a clean Arch installation, the following packages are 'required' for basic use:
- bspwm (window manager)
- sxhkd (macro key bindings)
- ARandR (monitor/dekstop layout)
- xfce (terminal emulator)

Optional packages:
- polybar
- thunar (file manager)
- chromium (browser)
- lxappearance (GTK theme manager)
- graphite-dark (GTK theme)
- nitrogen (wallpaper manager)
- htop ('task manager')
- picom (window compositor)
- mpv (media player)
- pulseaudio (audio control)
- nvidia (graphics card driver)
## installation
Clone this repository and run `.\install.sh` the configuration. This will create a local backup of all config files that are replaced, so that when you choose to `.\uninstall.sh`, the original configuration is restored.
