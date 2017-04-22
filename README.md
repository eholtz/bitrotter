# bitrotter
Flips random bits on devices

Usage:

gcc -o bitrotter ./bitrotter.c
./bitrotter <device to damage>

e.g.:
./bitrotter /dev/sda

You obviously need access to the drive. Also it would be good to have a backup...

I used this to create damaged xfs filesystems.
