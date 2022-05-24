# resonance
A clean, feature-rich Arch configuration
## preview

## requirements
The easy way is to install the latest EndeavourOS with bspwm as a window manager. This will also set up all components for usage comfort, such as audio control, networking, etc.<br/>
However, if you want to use a clean Arch installation, the following packages are recommended for basic use:
- bspwm (window manager)
- sxhkd (macro key bindings)
- ARandR (monitor/dekstop layout)
- xfce (terminal emulator)
- polybar

Optional packages:
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
1. Create a backup of your `~/.config` folder
2. Clone this repository, then run:
`stow --target=${HOME} */` in the root of this repo.
This will symlink the git dotfiles to your `~\.config`. 
3. Install the Graphite-Dark GTK theme. You may use my patched version,
which removes the rounded corners on pop-up windows: `sudo cp gtk.css /usr/share/themes/Graphite-dark/gtk-3.0` or `cp gtk.css ~/.themes/Graphite-dark/gtk-3.0` depending on where you installed the theme.
