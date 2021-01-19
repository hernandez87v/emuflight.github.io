## VTX Power on an aux-mode switch

New in 0.3.3+, Adds an option to change vtx power with an aux channel.
 More info on usage: https://github.com/betaflight/betaflight/wiki/VTX-CLI-Settings

Example cli settings:

6-Position example on AUX6:
```
vtx 0 7 5 1 0 900 1100
vtx 1 7 5 2 0 1100 1300
vtx 2 7 5 3 0 1300 1500
vtx 3 7 5 4 0 1500 1700
vtx 4 7 5 6 0 1700 1900
vtx 5 7 5 8 0 1900 2100
```

2-Position example on AUX7:
```
vtx 6 6 0 0 1 900 1200
vtx 7 6 0 0 2 1800 2100
```

The above 2-Position example uses AUX7 ( channels are zero indexed, change to whatever channel number you have set up on the radio minus 1) and will switch between power modes 1 and 2 when aux-mode switch is within related ranges.

Easiest way to tell is to enable the VTX OSD element. You will see power change in the OSD. Make sure you have armed the quad once (to make sure you are not in lowpower disarm mode)
Note:

For Smart audio, the power levels are hardcoded in EmuFlight 0.X.Y as:
* 1: 25mw
* 2: 200mw
* 3: 800mw

***Make sure not to use more than the vtx allows.***

[Unsure if this applies to Tramp; power-levels are preset in the vtx itself.]