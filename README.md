# XConceal
XConceal is a script for minimizing and maximizing windows in X11.

## Install
Run as root to install globally or as other user to install locally:
```
make install
```

## Usage
```
Usage: xconceal <command> <args>

Commands:
  help - display help
  hide - hide active window if no arguments are given
         otherwise hide a window with given id
  show - show a minimized window with given id
  select - display a list of minimized windows and select one
```
You can set variable `DMENU` to for example `rofi -dmenu` if instead of `dmenu` you want to use `rofi`.
