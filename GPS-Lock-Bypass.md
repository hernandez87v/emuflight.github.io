Bypassing the satellite lock requirement may be a safety issue.  We do _not_ recommend such; However, it is frequently asked if such is possible.  This is technically possible with `set gps_rescue_min_sats = 0`.  Default is `8`.

@glossy_fpv Tip: Just remember that if you hit return to home or failsafe and you took off with 0 sats you will not return home. Use min 6 sats to return home.


***

Do you want failsafe-drop and GPS-rescue on a switch?

@daveskybiker tip: Min sats 0, gps rescue on a switch, failsafe drop. Just get 6 min sats before you arm if you want gps rescue.