# A Network Time Protocol client for the Wii

## Prerequisites

DevKitPro: 

## Building

Run this command:
```
git clone https://github.com/testing-platform-games/wii-ntp-cloudflare.git
```

Run `make` with the variable `DEVKITPPC` set to the path of devkitPPC (as an environment variable or an argument passed thereto).

## Usage

In its simplest usage, launch the application without any arguments, at which point you can select the UTC offset of your time zone with the D-Pad of any connected Wii Remote or GameCube controller. After selecting your time zone, press A to continue.

Additionally, this application supports the following arguments:
```
-t, --timezone <UTC offset>	the UTC offset of your time zone

-a, --auto			set the time without any user interaction,
				with a 5 second period to be interrupted
				(overrides previous instances of -w)

-w, --wait			wait for the user to press A to set the time,
				allowing for the UTC offset to be selected
				(default, overrides previous instances of -a)
```

## License
And I, (the person who forked this repo), quotes:

"I dedicate the contents of this repository to the public domain via Creative Commons CC0 1.0 Universal \(a copy of which can be found in `LICENSE.txt`\). Additionally, this code contains several excerpts from systemd-timesyncd, licensed under the GNU Lesser General Public License as published by the Free Software Foundation, either version 2.1 of the License, or (at your option) any later version."
 - Galaxy Master 
