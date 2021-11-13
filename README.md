# Kensington Expert Trackball Configuration


This is a configuration script for the Kensington Expert trackball that remaps some of the buttons and edits some props.

This scripts dependancies are `xinput` `grep` and `sed` which should be installed on all distros by default.

There are comments in the script which should help you setup your own config.

# Layout

If you run the script as is without changing anything this will be your layout:
```
______________   _________  ________________
| back       |   |       |  | right click  |
--------------   |       |  ----------------
______________   |       |  ________________
| left click |   |       |  | middle click |
--------------   ---------  ----------------

```
1. Natural scrolling will be enabled. ( scrolling is smoother with this on )
2. Ball acceleration will be disabled.
3. Middle click + ball roll can also be used to scroll. ( very smooth and fast scrolling )

# Usage

You can run the script simpy by calling the script as a standard user

Or a better way is to put it in your desktop environment or window manager config, so that it runs when you login, the script also checks if the trackball is present before running any commands so its safe to use it like this.

I use with with an autostart file which has also been included for reference.
