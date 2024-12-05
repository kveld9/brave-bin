# brave-bin
Template file for Brave Browser for Void Linux distribution. Binary version.

## Installation steps.
1. Download this repo as a zip.
2. Extract the content.
3. Rename the folder ```brave-bin-main``` to ```brave-bin```.
4. Move the folder to ```void-packages/srcpkgs```.
5. Execute ```./xbps-src pkg -j$(nproc) brave-bin```. # remember to stay in the void-packages directory.
6. Install the package by executing ```xi brave-bin```. # remember to have installed "xtools" package for "xi" command.


## Credits.
- [brave-browser](https://github.com/brave/brave-browser)
- [brave-bin - AUR](https://aur.archlinux.org/packages/brave-bin)
- [xbps-src](https://github.com/void-linux/void-packages)
