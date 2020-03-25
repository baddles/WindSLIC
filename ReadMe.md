WindSLIC SLIC injectors
=======================

includes UEFI, NTFS, bootmgr SLIC injectors and installers.

This fork, by baddles, is aimed at providing the third/fourth(? - not sure cuz I forgot as of writing this - 25/Mar/20) argument during installation, to relocate Microsoft's BootMGFW.efi's folder location.

This is useful in scenarios where you need to rename path 'EFI\Microsoft\Boot\Bootmgfw.efi' to something else to install other bootloader in the same place alongside Microsoft's EFI, e.g. Clover/OpenCore/Grub, due to the lock that BIOS manufacturer created that will boot this file instead of 'EFI\Boot\Bootx64.efi'.
