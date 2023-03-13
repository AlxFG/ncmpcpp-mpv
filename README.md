# ncmpcpp-mpv

uses mpv to display ablum art inside of ncmpcpp taking advantage of your window
manager's window rules to place the mpv window to the desired location.

## purpose

use mpv to display album art regardless of using X11 or wayland insted of
ueberzug which only supports X11, with a caveat being 2 windows instead of 1
which is less ideal. this is for personal my personal use after not being able
to get album art while using sway.

## disadvantages

* uses 2 windows instead of one
* implementation is hacky
* won't resize based on window size

## TODO

* improve implementation
* add example window rules for some window managers
* use `mpv --geometry` instead of relying window rules

## credits
https://github.com/tam-carre/ncmpcpp-ueberzug
