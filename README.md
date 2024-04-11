# Embedded Sound Player

This project implements an embedded sound player using a STM microcontroller and a Raspberry Pi. The STM microcontroller is connected to a matrix keypad and an LCD screen, while the Raspberry Pi acts as a server, playing audio files. Communication between the STM and the Raspberry Pi is done via serial communication. The Raspberry Pi sends information about the currently playing song and its status (playing or paused) to the STM. The STM sends keyboard instructions read from the keypad to the Raspberry Pi, including commands to play, pause, skip to the next track, or stop playback.

## Overview

The repository contains two folders:
- **raspberry**: Contains the code for the Raspberry Pi.
- **stm**: Contains the code for the STM microcontroller.
- **schematic**:  A schematic diagram of the connections.

## Demo

A video demonstration of the project is available:

[![Demo del Proyecto](http://img.youtube.com/vi/Ow90lmI1I0Y/0.jpg)](https://www.youtube.com/watch?v=Ow90lmI1I0Y)

## Usage
1. Connect the LCD and the keyboard.
2. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/EmbeddedSoundPlayer.git
3. Upload the code to each device and run it.

## Schematic
The schematic file shows how to connect all the components needed
