KFROBOT_RP2040

Arduino Board Manager package for KFROBOT_RP2040

Version: 1.0.0
Core Base: Arduino-Pico 5.5.1
Status: Stable
Supported OS: Windows
Arduino IDE: 2.x

Installation

1. Add Boards Manager URL

Open Arduino IDE:

File → Preferences → Additional Boards Manager URLs

Add:

https://raw.githubusercontent.com/frame007/KFROBOT_RP2040_Board_Manager/main/package_kfrobot_rp2040_index.json

Click OK.

2. Install KFROBOT_RP2040

Open:

Tools → Board → Boards Manager

Search:

KFROBOT

Select:

KFROBOT RP2040 Boards

Choose version 1.0.0 and click INSTALL.

3. Select the board

Open:

Tools → Board → KFROBOT RP2040 Boards → KFROBOT_RP2040

Then select the correct COM port.

Quick Test

#include <KFROBOT.h>

void setup() {
  KFROBOT.begin();
  KFROBOT.beep(2000, 100);
}

void loop() {
}

Compile and upload normally from Arduino IDE.

Included Components

KFROBOT_RP2040 board definition

RP2040 core based on Arduino-Pico 5.5.1

KFROBOT Library

ARM GCC toolchain

Python runtime

Picotool

Required Adafruit libraries

Custom KFROBOT pin variant

No separate Raspberry Pi RP2040 board package is required for normal KFROBOT_RP2040 use.

KFROBOT Library

The package includes support for:

Buzzer

Buttons

Servo control

Motor control

Encoder reading

MCP3008 sensor reading

BNO08x Gyro

SSD1306 OLED

Robot movement and line-tracking functions

Board Information

Board name:

KFROBOT_RP2040

Architecture:

rp2040

Default CPU:

125 MHz

Flash:

2 MB

Release

V1.0.0

First stable release.

Installable through Arduino Boards Manager

Compile tested

Upload tested

Clean installation tested on multiple Windows computers

Standalone package does not require a separate Raspberry Pi RP2040 Boards Manager installation

Download

GitHub Releases:

https://github.com/frame007/KFROBOT_RP2040_Board_Manager/releases

Credits

KFROBOT_RP2040 is based on the Arduino-Pico RP2040 core by Earle F. Philhower, III.

This distribution also includes third-party libraries and components. Their original license and copyright files should be retained with the distributed package.

Maintainer

KFROBOT

GitHub:

https://github.com/frame007/KFROBOT_RP2040_Board_Manager
