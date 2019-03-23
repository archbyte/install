## USE AT YOUR OWN RISK. 

**My setup: Lenovo X1 Carbon 120GB SSD (GPT-UEFI)**

**Boot into the arch install media and run the following commands.**

wifi-menu (for wifi)

pacman -Sy reflector git

reflector --verbose -l 100 -p http -p https --sort rate --save /etc/pacman.d/mirrorlist

git clone https://github.com/archbyte/install --branch fast1

/bin/bash install/arch

**Login by entering your username and password.**

./gnome1

OR

./i3xfce1 ~ IN PROGRESS

OR

./kde1 ~ IN PROGRESS

**Enjoy.**
