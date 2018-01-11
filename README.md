# image-pipeline
Image resizing pipeline for mac

Place images in a folder on your mac and they will be resized and output into another directory.

# Use cases
* camera imports
* Android screenshot imports

# Requirements
* Python 3.5
* macOS

# Installation
1. Clone this repo `git clone https://github.com/supercoffee/image-pipeline`
2. Run the install script `./install`

# Configuration
Edit the file `~/.image-pipeline.conf` with your favorite text editor

## Reference

```
# Resize images from DCIM to camera-jpegs, resizing them to a max dimension of 1920px
from ~/Pictures/DCIM to ~/Pictures/camera-jpegs/ resize maxDimension=1920

```

# Uninstalling

Uninstalling will not remove this project from your computer, it only removes the installed scripts and daemons.
Use the `--clean` flag to remove the config files from your home directory.

From this project directory:
```
./uninstall

# -- OR --

./uninstall --clean
```
