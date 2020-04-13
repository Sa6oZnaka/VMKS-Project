# VMKS PROJECT

For raspberry PI 4 change PIN 4 to PIN21
and use lower freq - under 90 MHz

1. Compile
``gcc -lm -std=c99 -g transmitter.c -o transmitter``
2. Start 
``sudo ./transmitter [song - wav file] [freq - float value]``

Here is a example
``sudo ./transmitter star_wars.wav 88.8``
