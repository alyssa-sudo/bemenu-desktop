# bemenu-desktop
A bunch of scripts to make bemenu/dmenu[^1] more DE-like


## starmenu
Starmenu is a start-menu made in bemenu with the option to run Apps, Programs, Files, and Settings.[^2]

Starmenu is in a broken state, will be fixed but as of now is only semi-functional.

## wimenu
Wimenu is a wifi-menu made in bemenu with the options to select known networks, forget, disconnect, etc.

Wimenu is not completed, here are the current bugs that exist in wimenu:
- Wifi Networks with spaces are currently broken.

Wimenu is exclusive to iwctl as of now, nm support will be in added in the future.

## blumenu
Blumenu is a bluetooth-menu made in bemenu, with options to list, scan, connect, forget, etc.

Blumenu is broken as of now, will be fixed if possible.

## noimenu
Noimenu is a sound-menu made in bemenu, with the option to select a device

Noimenu is in a working state with pactl, however more features are planned, such as:
- Using human readable names for the audio devices.
- Selecting a audio device allowing you to change the volume with a slider. (if possible)

## powmenu
Powmenu is a power-menu made in bemenu, with the option to Shutdown, Restart, Sleep, and Cancel.

Powmenu is in a working state, currently works with loginctl.

[^1]: Dmenu support is a planned feature and is secondary to bemenu support.
[^2]: Starmenu is going to be a large undertaking being that if possible, I will create an entire settings app within bemenu.
