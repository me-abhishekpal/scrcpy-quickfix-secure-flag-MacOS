# scrcpy-quickfix-secure-flag-MacOS
Build for MacOs against issue of Crash on Android 12 Developer Preview 1, added quickfix secure flag DONOTMERGE


# Clone this repo
# cd into the folder and issue the commands accordingly:

# Run without installing:
./run x [options]


# Install
After a successful build, you can install scrcpy on the system:

sudo ninja -Cx install

This installs three files:

/usr/local/bin/scrcpy
/usr/local/share/scrcpy/scrcpy-server
/usr/local/share/man/man1/scrcpy.1

You can then run scrcpy.

# Uninstall
sudo ninja -Cx uninstall  # without sudo on Windows
