## WindowsVersion winver

Win PE Find version of the OS on a computer's disk. Looks for a well known Windows file ntoskrnl.exe, gets version and prints result.

Designed for use during computer recycling, assumes the OS is licensed and that a reinstall would activate properly. Boot to straight to Win PE, check OS and then proceed with installation.

Designed to run in Win PXE this involves statically linked libraries, setup in VS project properties.


F:>WindowsVersion

C: Not Found

E: Windows 10 Version: 6.2.19041.4780 

X: Windows 10 Version: 6.2.18362.418 

F:>

This shows that the hard disk (E:) has a windows 10 installation, X: is the Win PXE OS
