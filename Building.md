Although building is possible on any platform, here is the Debian/Ubuntu method.

one time:
```
sudo apt install git build-essential
git clone https://github.com/emuflight/EmuFlight.git
```

build:
```
cd EmuFlight

#on occasion when arm_sdk changes:
make arm_sdk_install --always-make

#build targets (single, list, or all):
make HELIOSPRING FOXEERF405 MATEKF722

# make all --keep-going
```

Note: this works with `git checkout [branch or commit]` also.