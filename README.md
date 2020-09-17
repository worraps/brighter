brighter
========

Laptop backlight brightness control

## Features

- Assign any system-wide hotkey combination to control dim/bright level of the backlight
- Honors system max_brightness
- Set dim/bright increment

## Requirements

- Tested with Python 3
- Install the [PyPI package](https://pypi.python.org/pypi/keyboard/):
    pip install keyboard

## Install

- download brighter
- edit hotkeys and increment
- copy **brighter** to /usr/bin/mykeys
```
user@laptop:~/src$ git clone https://github.com/worraps/brighter.git
user@laptop:~/src$ cd brighter/
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


