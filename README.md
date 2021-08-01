# Minecraft-Torch-CPB
Minecraft Bluetooth Torch using Adafruit circuit playground bluetooth and Neo-pixel ring


This code is based upon the youtube series and work by Prof. John Gallaugher
His videos at https://YouTube.com/profgallaugher Follow on Twitter: @gallaugher

This work uses the following components:
-  Adafruit Circuit Playground Bluetooth
- Adafruit NeoPixel Ring x12
- Micro-USB D to USB-C cable to work with the CPB.

The torch is 3d printed using:
    https://www.thingiverse.com/thing:2002669
    
We printed ours in PLA, then spray primed and finished using acrlylic paints. The torch top was printed in transparent PLA using minimum infil patern and density. 

On a creality3D Ender 3 Pro, using CURA the base print had a dimensons of 50mm x 50mm x object height, in order to fit the CFB comfortably with a lithium battery we uniformly scaled up the projects x, y dimensions from 50mm up to 60mm x 60 x object height. 

Ours was printed using the "Base upright" "Shaft" and "Head" stl files sliced to the ideal settings for our particular fillament and appetite for speed & quality. 

Depending on your slicer you may need to fix the grid failures in the base STL outside of your slicer. (CURA d

Make sure your CircuitPlayground Bluefruit (CPB) has the latest version of CircuitPython.
The "lib" folder on your CPB should have the following folders or files:

- adafruit_ble
- adafruit_bluefruit_connect
- adafruit_bus_device
- adafruit_circuitplayground
- adafruit_led_animation
- neopixel.mpy
- simpleio.mpy

The latest CircuitPython .uf2 file and the latest library files can be downloaded from:
    https://circuitpython.org




