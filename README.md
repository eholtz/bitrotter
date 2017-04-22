# bitrotter
Flips random bits on devices

# how to compile
```
gcc -o bitrotter ./bitrotter.c
```

# how to use
```
./bitrotter <device to damage>
```

# example
```
./bitrotter /dev/sda
```

# trivia
You obviously need access to the drive. Also it would be good to have a backup...

I used this to create damaged xfs filesystems.
