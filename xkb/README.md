# US layout extended with Hungarian characters for XKB

The [us_hu](us_hu) file adds Hungarian characters and the Euro sign to the US layout.

## The characters

| Key combination | Character |
| --------------- | :-------: |
| Right Alt + A   | á |
| Right Alt + E   | é |
| Right Alt + I   | í |
| Right Alt + O   | ó |
| Right Alt + P   | ö |
| Right Alt + [   | ő |
| Right Alt + U   | ú |
| Right Alt + Y   | ü |
| Right Alt + T   | ű |
| Right Alt + 5   | € |

## How to try

1. Copy the file [us_hu](us_hu) to `/usr/share/X11/xkb/symbols` folder.
2. Run the following command: `setxkbmap us_hu`

## How to make it persistent in OpenSUSE

1. Copy the file [us_hu](us_hu) to `/usr/share/X11/xkb/symbols` folder.
2. Modify the `/etc/vconsole.conf` and `/etc/X11/xorg.conf.d/00-keyboard.conf` files.

### Caveats

1. I couldn't make the new layout to show up in *YaST Keyboard*.
2. As soon as you execute *YaST Keyboard* (even if you click *Cancel*) the old layout (*English (US)* in my case)
will be used.

## How to make it persistent in Linux Mint Debian Edition (LMDE)

1. Copy the file [us_hu](us_hu) to `/usr/share/X11/xkb/symbols` folder.
2. Modify the `/etc/default/keyboard` file and set `XKBLAYOUT` to `us_hu`.

