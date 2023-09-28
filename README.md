# live-installer
A live installer for LMDE (Linux Mint Debian Edition).
This fork provides the option to format root partition using btrfs, which can be used together with LUKS/LVM to have encrypted root/swap partitions.
Subvolumes are designed for easy snapshots using snapper and for [grub-btrfs](https://github.com/Antynea/grub-btrfs) integration.

# Usage
## Normal installation
`/usr/bin/live-installer`

## Expert installation
This allows for installing to self prepared `/target` mountpoint with self creation of fstab, crypttab, etc.

`/usr/bin/live-installer-expert-mode`
