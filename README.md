## USE WITH CAUTION. THIS MAY LEAVE YOUR SYSTEM IN AN UNUSABLE STATE.

**Boot into the arch install media and run the following commands.**

wifi-menu (for wifi)

pacman -Sy reflector git

reflector --verbose --latest 100 --protocol http --protocol https --sort rate --save /etc/pacman.d/mirrorlist

git clone https://github.com/customlinux/arch

mv arch/archinstall $PWD

chmod +x archinstall

./archinstall

**When in  chroot, run the below commands.**

./chrootinstall

exit

reboot

**Login by entering your username and password.**

./postinstall


## Welcome to Arch Linux.
