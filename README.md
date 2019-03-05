## Use only if you understand how to manually install Arch. 

**My setup: Lenovo X1 Carbon 120GB SSD (GPT-UEFI)**

**Boot into the arch install media and run the following commands.**

wifi-menu (for wifi)

pacman -Sy reflector git

reflector --verbose -l 100 -p http -p https --sort rate --save /etc/pacman.d/mirrorlist

git clone https://github.com/archbyte/install --branch fastinstall

/bin/bash install/arch

**Login by entering your username and password.**

./de

**Enjoy.**
