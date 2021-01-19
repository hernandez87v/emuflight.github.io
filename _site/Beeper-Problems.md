# BEEPER FIX'S

## NONSTOP BEEPER

Quick fix for beeper issues some users have experienced. The issue comes with some bad beeper defaults brought from butterflight. Simply typing this into the cli should remove the last few beeper presets you may not want that are probably causing your beeper to beep nonstop. 

```python
set beeper GPS_STATUS = off
set beeper CRASH FLIP = off
set beeper CAM_CONNECTION_OPEN = off
set beeper CAM_CONNECTION_CLOSED = off
set beeper RC_SMOOTHING_INIT_FAIL = off
```

## NO BEEPER

If your beeper just does not seem to be working at all then for the time being this code put into your cli should turn on your beepers.

```python
beacon RX_LOST
beacon RX_SET
```
