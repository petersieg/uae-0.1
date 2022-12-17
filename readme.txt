(from my hopefully fresh enough memory)

prepare:
1. Create a new virtualbox debian 32-bit VM with 1MB ram and 10GB new hdd.
2. Download: iso #1 from: https://cdimage.debian.org/mirror/cdimage/archive/8.11.1/i386/iso-dvd/
3. place in virtual optical VM drive and boot from it.
4. Install default debian8.
5. Boot into fresh installed debian8
6. su
7. apt install build-essential libX11-dev libXext-dev
(Did not found: imake; libXExExt-dev; libsdl-dev)
(libXExExt commented out in Makefile)

compile:
1. Expand uae-0.1.zip in $HOME; cd into it
2. run make

run:
1. place kick.rom file in same directory as uae is located. Use 2.x version for "animated" floppy image.
2. ./uae
3. f <return> in debugger terminal window.

