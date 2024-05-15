# bemenu-desktop
A bunch of scripts to make bemenu/dmenu[^1] more DE-like


## starmenu
Starmenu is a start-menu made in bemenu with the option to run Apps, Programs, Files, and Settings.[^2]

Starmenu is in a broken state, will be fixed but as of now is only semi-functional.

![image](https://github.com/alyssa-sudo/bemenu-desktop/assets/83582297/ce817109-0fb7-48ed-aad2-58527783698d)

## wimenu
Wimenu is a wifi-menu made in bemenu with the options to select known networks, forget, disconnect, etc.

Wimenu is not completed, here are the current known bugs that exist in wimenu:
- Wifi Networks with spaces are currently broken.

Wimenu is exclusive to iwctl as of now, nm support will be in added in the future.

![image](https://github.com/alyssa-sudo/bemenu-desktop/assets/83582297/cb1a6483-8f68-40e7-8220-2be754491738)

## blumenu
Blumenu is a bluetooth-menu made in bemenu, with options to list, scan, connect, forget, etc.

Blumenu is broken as of now, will be fixed if possible.

![image](https://github.com/alyssa-sudo/bemenu-desktop/assets/83582297/0e5415e9-3d6a-4fb3-a4bc-4fa67e12f746)

## noimenu
Noimenu is a sound-menu made in bemenu, with the option to select a device

Noimenu is in a working state with pactl, however more features are planned, such as:
- Using human readable names for the audio devices.
- Selecting a audio device allowing you to change the volume with a slider. (if possible)

![image](https://github.com/alyssa-sudo/bemenu-desktop/assets/83582297/435c31bf-f62f-4baa-8179-79faa29656f0)

## powmenu
Powmenu is a power-menu made in bemenu, with the option to Shutdown, Restart, Sleep, and Cancel.

Powmenu is in a working state[^3], currently works with loginctl.

- Large but listen in footnote.

![image](https://github.com/alyssa-sudo/bemenu-desktop/assets/83582297/b361cbf2-dd20-4075-afca-a1a1c5257769)

[^1]: Dmenu support is a planned feature and is secondary to bemenu support.
[^2]: Starmenu is going to be a large undertaking being that if possible, I will create an entire settings app within bemenu.
[^3]: Use with caution, as powmenu as of now, sees "return" on anything but "Cancel" as selecting an option, YOU WILL ACCIDENTALLY SHUT OFF YOUR PC IF YOU DO NOT ACKNOWLEDGE THIS.
