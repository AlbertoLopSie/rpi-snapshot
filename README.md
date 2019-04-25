# rpi-snapshot
Makes a bootable snapshot of rootfs on another partition

The idea is to be able to generate a quick snapshot of the active mounted rootfs
on another boot disk partition and optionally modify cmdline.txt on boot
partition to reboot over that image

The script modifies the fstab on cloned partition to the new partition structure
