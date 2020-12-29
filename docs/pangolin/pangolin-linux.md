# Pangolin-linux
Pangolin Desktop running on Linux systems.

## Requirements

### Debian/Ubuntu

- install git and matchbox-window-manager
```
sudo apt install git matchbox-window-manager
```
- Install flutter

```bash
git clone https://github.com/flutter/flutter.git
cd flutter/ && sudo export PATH="$PATH:`pwd`/flutter/bin"
```
Then open .bashrc and add this line to it
```bash
export PATH="$PATH:[~/flutter/]/flutter/bin"
```
Open a new terminal and Verify that the flutter command is available by running
```
which flutter
```
### arch

- Install flutter 
```
yay -S flutter
```
- Install matchbox-window-manager
```
sudo pacman -S matchbox-window-manager
```

## Installation

If you're using something other than Linux Mint you will get a nosnap error but this won't effect anything.
```bash
git clone https://github.com/HexaOneOfficial/pangolin-linux.git
cd pangolin-linux && sudo chmod +x install.sh && sudo ./install.sh
```
- now restart and login with pangolin

## License

<p align="left">
  <img width="45%" src="https://github.com/dahliaos/brand/blob/master/Logo%20SVGs/dahliaOS%20logo%20with%20text%20(drop%20shadow).svg"
</p>

Copyright © The dahliaOS authors, contact@dahliaos.io

This project is licensed under the [Apache 2.0 license](../LICENSE)
