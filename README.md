# scrcpy-quickfix-secure-flag-MacOS

All credit goes to the original author(https://github.com/Genymobile/scrcpy/commits?author=rom1v), I just created the build for the unknown.

Build for MacOs against issue of Crash on Android 12 Developer Preview 1, added quickfix secure flag DONOTMERGE(https://github.com/Genymobile/scrcpy/commit/01199084adfe7d0f4c3bdebff7f4646772bcd196)


If you have any issues running the below commands, make sure you've done these steps:

Mac OS

Install the packages with Homebrew:




**runtime dependencies**

_brew install sdl2 ffmpeg_



**client build dependencies**

_brew install pkg-config meson_



**Clone this repo**
cd into the folder and run the commands according to your need:

_cd path-to-this-downloaded-repo_


**Run without installing:**
./run x [options]


**Install**
After a successful build, you can install scrcpy on the system:

sudo ninja -Cx install

This installs three files:

/usr/local/bin/scrcpy
/usr/local/share/scrcpy/scrcpy-server
/usr/local/share/man/man1/scrcpy.1

You can then run scrcpy.

**Uninstall**
sudo ninja -Cx uninstall  # without sudo on Windows
