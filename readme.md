# AUR Package for Brother DCP 145C Printer Drivers

## Summary

This AUR package provides drivers for the Brother DCP 145C printer only.

## Installation

Recommended installation is direct from the AUR using your package manager of choice (e.g. `yaourt -S brother-dcp-145c`).

To install from source, compile the package (using `makepkg`), and then install the compiled `*.pgk.tar.xz` using a package manager (such as `pacman`).

## Changing Paper Size

Due to incompatibilities between the Brother drivers and CUPS, in order to change the paper size with correct printing alignment, it is necessary to edit a configuration file located at `/usr/share/brother/Printer/dcp145c/inf/brdcp145crc`.

The default paper size is Letter. In order to change this to A4, change the line `PaperType=Letter` to `PaperType=A4`.

