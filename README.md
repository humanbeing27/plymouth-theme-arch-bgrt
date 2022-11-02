# Install
### Build 
```sh 
git clone https://github.com/humanbeing27/plymouth-theme-arch-bgrt.git arch-bgrt
cd arch-bgrt
makepkg -sircfC
```
### Install using prebuilt Package
The prebuilt package is available in releases and can be installed using:
```sh 
sudo pacman -U ./plymouth-theme-arch-bgrt-2-1-any.pkg.tar.zst 
```
# Set as Theme
```sh
sudo plymouth-set-default-theme -R arch-bgrt 
```
