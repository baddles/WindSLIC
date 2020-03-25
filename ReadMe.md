WindSLIC SLIC injectors
=======================

includes UEFI, NTFS, bootmgr SLIC injectors and installers.

This fork, by baddles, is aimed at providing the third/fourth(? - not sure cuz I forgot as of writing this - 25/Mar/20) argument during installation, to relocate Microsoft's BootMGFW.efi's folder location.

This is useful in scenarios where you need to rename path 'EFI\Microsoft\Boot\Bootmgfw.efi' to something else, in order to install other bootloader in the same place alongside Microsoft's bootloader, e.g. Clover/OpenCore/Grub, due to the lock that BIOS manufacturer created that will boot this file instead of 'EFI\Boot\Bootx64.efi'.

As of writing this, no changes have been made to the files yet, except the readme update. Expect the changes to happen in the next couple of days.
