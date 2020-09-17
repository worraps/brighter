brighter
========

Laptop backlight brightness control for Linux

## Tested on
- Ubuntu 20.04 LTS
- HP ZBook 15

## Features

- Assign any system-wide hotkey combination to control dim/bright level of the backlight
- Honors system max_brightness
- Set dim/bright increment

## Requirements

- Tested with Python 3
- Install the [PyPI package](https://pypi.python.org/pypi/keyboard/):
    pip install keyboard

## Install

```
user@laptop:~/src$ git clone https://github.com/worraps/brighter.git
user@laptop:~/src$ cd brighter/
user@laptop:~/src$ nano brighter
```
- Edit defaults
```
DIMMER='ctrl+alt+shift+F2'
BRIGHTER='ctrl+alt+shift+F3'
INCREMENT=10000
```
- Press Ctrl-X to save and exit (if using nano)
```
user@laptop:~/src/brighter$ sudo cp brighter /usr/bin/brighter
user@laptop:~/src/brighter$ sudo chmod +x /usr/bin/brighter 
```

## Usage

- Execute brighter from terminal
    `user@laptop:~$ sudo brighter`
- Press hotkey combination to increase/decrease brightness
- Press ESC when finished

## TODO

- make setup package
- move config to /etc/


