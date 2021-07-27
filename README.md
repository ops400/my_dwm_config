# my_dwm_config
You will need the Ubuntu font family and the base-devel package on arch linux, I don't know what package you will need on debian or gentoo.
Pls rename the git folder to .git .
OH! The default terminal on my config is the suckless st.
# NEEDED PACKAGES
base-devel
xorg-server
xorg-xinit
libx11
libxinerama
libxft
webkit2gtk
terminus-font

# Installation Guide
1: do this command: sudo pacman -S base-devel xorg-server xorg-xinit libx11 libxinerama libxft webkit2gtk terminus-font

2: copy the dwm folder to your home directory and rename the git folder wich is inside of the dwm folder to .git

3: go to your dwm and do this command: sudo make clean install

# Warning These are for arch linux and I don't know what package you will need on debian or gentoo, or if will work on debian or gentoo.
