# BPI-WiringPi2

```
Author:   hexzhen3x7
Version:  0.2a
Github:   https://github.com/bpi-codehunterz-world/BPI-WiringPi2
Website:  https://codehunterz.world || https://blackzspace.de
```


Description:

This is a modified WiringPi - Libarys for Banana Pi's !"

I DO NOT OWN ANY RIGHTS !!


To compile your applications with wiringPi use:

Example:
```sh

gcc -o out_app in_file.c -lwiringPi
```

to your compile line(s) To use the Gertboard, MaxDetect, etc.
code (the devLib), you need to also add:

```sh
gcc -o out_app in_file.c -lwiringPiDev
```
to your compile line(s)."