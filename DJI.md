DJI compatibility has NOT been focused on.

* ***DJI devices may bypass USB arming block, DO NOT attempt arming DJI component based quads while plugged into Configurator, especially with propellers mounted. Always Props-off! This is always how things should be done, but be warned that DJI will cause arming to be allowed in the Configurator! Use a smoke-stopper for added protection.***

| UI  | Note  |
|---|---|
|PID PROF| working|
|| |
|PID >| |
|ROLL P| working|
|ROLL I| working|
|ROLL D| working|
|ROLL F| LOW ANGLE ERROR D|
|PITCH P| working|
|PITCH I| working|
|PITCH D| working|
|PITCH F| no effect|
|YAW P| working|
|YAW I| working|
|YAW D| working|
|YAW F| HIGH ANGLE ERROR D|
|| |
|MISC PP >| |
|FF TRANS| will not change|
|ANGLE STR| will not change|
|HORZN STR| will not change|
|HORZN TAS| will not change|
|AG GAIN| will not change|
|AG THR| will not change|
|THR BOOST| working|
|| |
|FILT PP >| |
|DTERM LPF| IN OSD starts at 25600 and when setting, it sets very large numbers in Matrix filter notch min, D |Term lowpass cutoff 1 (21870 and 63076 when set to 25590)|
|DTERM LPF2| Reading 0 instead of setting in config which is 250. setting it in osd has no efffect, but it |allows change in the osd|
|DTERM NF| Reading 0 and setting it has no effect in cli or config|
|DTERM NFC0| setting between 0,1,2,3,4 Gyro Notch Filter 2 Center Frequency [hz] moves to 0 (disable in gui), |256, 512, 768, 1024|
|YAW LPF| IN OSD 25600 and when setting, affects dterm_lowpass_hz_pitch and dterm_lowpass_hz_yaw (large negative  |number and 99)|
|| |
|RATE PROF>| working|
|RATE>| |
|RC, SUPER, EXPO| working|
|THR MID| working|
|THR EXPO| working|
|THRPID ATT| working (TPA P)|
|TPA BRKPT| working (TPA Breakpoint)|
|| |
|"FLIT" GLB > (dji typo)| |
|GYRO LPF| 26880 at start, and when setting, it affects gyro_lowpass_hz_pitch and gyro_lowpass_hz_yaw in cli |(-7821, and 104)|
|GYRO LPF2| 0,1,2,4 in osd. no difference in config or diff|
|GYRO NF1 | no effect, setting not saved|
|GYRO NF1C | OSD Does not allow change|
|GYRO NF2| setting numbrs 0,1,2,3 does 256, 512, 768 on gyro_notch2_cutoff. also affects dterm_lowpass_hz_yaw ?|
|GYRO NF2C | no effect, setting not saved|
|| |
|COPY PID PROFILE| working|
|COPY RATE PROFILE|| working|