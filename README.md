# Extras for Dieter Mueller DRC2 Homebrew Computer

Extras:
* [Computer schematic as PDF](docs/comp-schematic.pdf)
* [Video card schematic as PDF](docs/video-schematic.pdf)
* [Keyboard module schematic as PDF](docs/keyboard-schematic.pdf)
* [Computer PCB as PDF](docs/comp-board.pdf)
* [Video card PCB as PDF](docs/video-board.pdf)
* [Keyboard module PCB as PDF](docs/keyboard-board.pdf)

To open the original schematics that you can find on
the [project website](http://www.6502.org/users/dieter/drc2/drc2.htm),
you can use Eagle 7.0. This program is still available,
along with other (both newer and older) versions [here](ftp://ftp.cadsoft.de/eagle/program/).
I managed to run Eagle 7.0 on Ubuntu 16.04 LTS without any problems.

To run version 4.x of Eagle I had to run [Fedora 7](https://archives.fedoraproject.org/pub/archive/fedora/linux/releases/)
inside VirtualBox. Because GuestAdditions where not working on such old system I had to copy the files to/from the
guest OS using SSH. This can be easily done if you set up port forwarding from Guest OS (`0.0.0.0 22`) to Host (`0.0.0.0 2222`).
I used both `scp` and `mc` commands to copy the files.



