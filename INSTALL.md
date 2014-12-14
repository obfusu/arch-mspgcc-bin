Installation
-------------

Install the packages in this order:

```sh
sudo pacman -U mspgcc-binutils-bin-20120406-1-x86_64.pkg.tar.xz
sudo pacman -U mspgcc-gcc-bin-20120406-1-x86_64.pkg.tar.xz
sudo pacman -U mspgcc-libc-bin-20120406-1-x86_64.pkg.tar.xz
sudo pacman -U mspgcc-msp430mcu-bin-20120406-1-x86_64.pkg.tar.xz
sudo pacman -U mspgcc-mspdebug-bin-20130718-1-x86_64.pkg.tar.xz
```

For msp430-gdb, install 'libtinfo' from AUR. Then install the package.
```sh
sudo pacman -U mspgcc-gdb-bin-20111205-1-x86_64.pkg.tar.xz
```
