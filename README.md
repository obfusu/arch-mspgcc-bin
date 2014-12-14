arch-mspgcc-bin
===============

GNU Compliler Suite for msp430 - binary packages for Arch linux and its derivatives  
(Based on mspgcc-20120406 LTS)


**Ref Links:**  
AUR (binutils,gcc,libc): https://aur.archlinux.org/packages/mspgcc-binutils-bin/  
AUR (mspdebug): https://aur.archlinux.org/packages/mspdebug/  
SourceForge (msp430mcu): http://sourceforge.net/projects/mspgcc/files/msp430mcu/msp430mcu-20120406.tar.bz2/download  
Launchpad (gdb - 20111205): https://launchpad.net/ubuntu/+source/gdb-msp430

**Upstream Link:**  
SourceForge(mspgcc): http://sourceforge.net/projects/mspgcc/  
SourceForge(mspdebug): http://mspdebug.sourceforge.net/

Packages:
  - mspgcc-binutils
  - mspgcc-gcc
  - mspgcc-libc
  - mspgcc-mcu		(Header Files and linker scripts, not actual binaries)
  - mspgcc-gdb		(Based on 20111205)
  - *mspdebug		(msp430 flasher - not part of mspgcc - try to install from AUR) 

  
Some of the mspgcc AUR links have not been updated and new users may find difficulty in setting up mspgcc on Arch Linux. Thus such users may utilize the ready-made pacman packages here. These packages were created from debian binary packages from Ubuntu repositories.

Note: Please make sure that mspgcc from other sources is not installed as it may lead to conflicts with pacman
