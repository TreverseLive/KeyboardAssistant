# Keyboard Assistant

**Keyboard Assistant** is a software designed to convert any point-and-click game into a keyboard-based game! It allows users to bind mouse movements and keyboard clicks to any valid keyboard key. This software is intended for personal, educational, and/or commercial use and is distributed under the terms of the custom license described in the LICENSE file.

Also included in this care package is Position.exe, which will display your mouse's current local AND global
position, every second! Simply press ENTER on your keyboard to copy the coordinates to your clipboard for
easy access!

## Table of Contents
1. Features
2. Installation
3. Configuration
4. License
5. Contact

## Features
 - Fully customizable keyboard shortcuts.
 - Works with any version of Windows.
 - Supports any and all ASCII characters, numbers, and arrow keys.
 - Your number of keybinds is only limited by your keyboard size.
 - Your number of supported coordinates is only limited by your monitor size.
 - Simultaneous, multi-monitor support; you can move across monitors!

## Installation
 - Download the most recent version of the .zip file from the GitHub repository (https://github.com/TreverseLive/Keyboard-Assistant/releases)
 - Unpack the .zip file to wherever you'd like, ensuring that all included files remain in the same directory.

### Prerequisites
Make sure you have the following installed on your system:
- Any software similar to Windows Command Prompt or Powershell

## Usage & Configuration

### Pause
To pause the program at any time, simply use the configurable pause hotkey found in the config.txt file! By
default, the hotkey is set to CTRL+SPACE.

### Configuration Files
 - All configuration can be accessed via the provided config.txt file.
 - To create custom keybinds, simply create a new .txt file in the same directory as Keyboard Assistant's .exe file, and type the name into the appropriate spot in the config.txt file!
     - To give you a little push, I also included fnaf.txt, which is already configured to play Five Nights
       at Freddy's, right off the bat!

### Supported command types:
Keyboard Assistant supports the following types of commands:
- **Click**: Move the mouse to a set of coordinates, wait, and click.
- **Move**: Move the mouse through multiple coordinates smoothly.
- **Drag**: Click and drag from one set of coordinates to another.
- **Delayed**: Move through multiple coordinates, then click and hold at the end.
- **KeyPress**: Press a key multiple times.
- **KeyHold**: Press and hold a key for a set duration.


### Click Command
Moves the mouse to a coordinate, waits, clicks, and holds for a duration.

**Example**:
Keybind=A
Type=Click
Coordinate1=100,100
Coordinate2=200,200
Wait=500
Hold=200
Mouse=1

### Move Command
Move the mouse through multiple coordinates smoothly.

**Example**:
Keybind=B
Type=Move
Coordinate1=100,100
Coordinate2=200,200
Coordinate3=300,300
Wait=200
Glide=500 **(optional)**

### Drag Command
Clicks at the first coordinate, drags through the others, and releases at the last one.

**Example**:
Keybind=C
Type=Drag
Coordinate1=50,50
Coordinate2=300,300
Coordinate3=400,400
Wait=300
Glide=500 **(optional)**

### Delayed Command
Moves through multiple coordinates, then clicks and holds at the last coordinate.
 
**Example**:
Keybind=1
Type=Delayed
Coordinate1=150,150
Coordinate2=250,250
Wait=1000
Hold=500
Mouse=Right
Glide=500 **(optional)**

### KeyPress
Presses a key multiple times with a specified delay between presses.

**Example**:
Keybind=2
Type=KeyPress
Wait=500
Press=5

### HeyHold Command
Presses and holds a key for a specified duration after a delay.

**Example**:
Keybind=/
Type=KeyHold
Wait=1000
Hold=3000

### Valid Inputs for Parameters

| Parameter         | Description                                                                  |
|-------------------|------------------------------------------------------------------------------|
| **Keybind**       | Any printable ASCII character (letters, symbols), number keys, or arrow keys.|
| **Type**          | `Click`, `Move`, `Delayed`, `Drag`, `KeyPress`, or `KeyHold`.                |
| **Coordinate(x)** | Any valid x,y formatted coordinate within the resolution of your monitor.    |
| **Wait**          | Any valid integer (time in milliseconds).                                    |
| **Hold**          | Any valid integer (time in milliseconds).                                    |
| **Glide**         | Any valid integer (time in milliseconds). **(optional parameter)**           |
| **Mouse**         | `1` (or left click) / `2` (or right click).                                  |
| **Press**         | Any valid integer (number of key presses for `KeyPress` command).            |

## License
This project is licensed under the terms described in the LICENSE file. You may use this software for personal, educational, and/or commercial purposes, but you may not redistribute or modify the core code. Please see the LICENSE file for more details.

## Contact
For any questions, concerns, or support, please feel free to reach out:

- **Treverse**
- **Email**: Treverse.Biz@Gmail.com
- **GitHub**: https://github.com/TreverseLive
- **Website**: https://Treverse.Live

If you’ve found this project useful and would like to support its development, you're welcome to contribute:

- https://streamelements.com/treverselive/tip

Your support is greatly appreciated, but by no means expected. Thank you for using **Keyboard Assistant**!
