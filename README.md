## Use only if you know how to manually install Arch. 

**Boot into the arch install media and run the following commands.**

wifi-menu (for wifi)

pacman -Sy reflector git

reflector --verbose --latest 100 --protocol http --protocol https --sort rate --save /etc/pacman.d/mirrorlist

git clone https://github.com/archbyte/install

/bin/bash $PWD/install/arch

**When in  chroot, run the below commands.**

./chroot

exit

reboot

**Login by entering your username and password.**

./post


## Welcome to Arch Linux.
