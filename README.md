[![Build Status](https://travis-ci.org/louisjdmartin/scripts_linux.svg?branch=master)](https://travis-ci.org/louisjdmartin/scripts_linux)

# scripts_linux
This repo group some linux script. Some are very usefull, like `netflix` which start netflix and a selected serie in fullscreen.

# Travis-CI
For now, it only check code quality with shellcheck

# Dependencies
```
apt update && apt install xdotool -y
```

# Scripts
- `netflix <serie>`: Start Netflix with selected serie or movie.
- `vol <+|-|0>`: Control the volume, can be used when computer is controlled with phone for example to change volume remotely.
