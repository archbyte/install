## Use only if you know how to manually install Arch. 

**My bios testing setup: 500GB HD (MBR-BIOS) | Dual Boot: Windows 10 LTSC + Arch Linux**

**Boot into the arch install media and run the following commands.**

wifi-menu (for wifi)

pacman -Sy reflector git

reflector --verbose --latest 200 -p http -p https --sort rate --save /etc/pacman.d/mirrorlist

git clone https://github.com/archbyte/install --branch testingbios

/bin/bash $PWD/install/arch

**When in  chroot, run the below commands.**

./chroot

exit

reboot

**Login by entering your username and password.**

./de

## Welcome to Arch Linux.
