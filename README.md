# TimersAndSerialComms
CODAL build tools for the micro:bit with my own program, ready to be built and flashed.

ALL CODE ASIDE FROM THE CW2.cpp IN microbit-v2-samples/source IS WORK OF VARIOUS MICROBIT DEVELOPERS AND RESEARCHERS RELATED TO THE MICROBIT FOUNDATION, I TAKE NO CREDIT FOR THAT CODE.

1. sudo apt install gcc
2. sudo apt install git
3. sudo apt install cmake
4. sudo apt install gcc-arm-none-eabi binutils-arm-none-eabi

THIS PROGRAM PROVIDES 3 FUNCTIONS:
1. 'Bit=Bang' a fixed string to serial every 240ms
2. Repeatedly read and display the Y value from the accelerometer
3. Make some noise through the on-board MicroBit speaker

4. Interface with the microbit, when runing this code, through a USB Serial monitor (I use vs-code's Microsoft-written extension)

Written November 2024 by Will Holbrook
