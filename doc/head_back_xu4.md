# XU4 version assembly

## Step 0: Wiring
Before starting, verify you have followed the steps explained in the [wiring documentation](wiring.md) concerning the audio and power connections.

## Step 1: Fix the audio amplifier
In this version, you can fix the audio amplifier to the head.

Put 2 M2.5 hex nuts in the holes at the bottom left:
![](img/assembly/XU4-audio-amp-1.jpg)

With 2x M2.5x6mm bolts you can now fix the amplifier on the head_back part:
![](img/assembly/XU4-audio-amp-2.jpg)

**NOTE: Unfortunately, the Odroid XU4 does not have audio output. If you want to use the audio, you will have to use a USB dongle and connect the audio jack to it.**

## Step 2: Fix the XU4 in the head
To fix the XU4, first ensure you have put 3x hex nuts on each holes:
![](img/assembly/XU4-xu4-1.jpg)

Place the XU4 like this:
![](img/assembly/XU4-xu4-2.jpg)

Screw the 3 M2.5x8mm bolts.

Note: the one on back of the head is pretty annoying to screw, sorry for that...

![](img/assembly/XU4-xu4-3.jpg)

## Connect cables
Now you have fixed all components, you can plug the cables.

There is only 2 USB port and if you want to plug the camera you need 3 ports. Therefore you will have to add a USB hub.

![](img/assembly/XU4-hub-1.jpg)

- plug the usb hub on one port
- plug the 3 usb devices on it
- connect the long 3 ways cable to one of the USB2AX and make it go through the hole at the back of the head
- connect the shorter 3 ways cable between the 2nd USB2AX and the Dynamixel AX12
- connect a 20cm 3 ways cable to the Dynamixel AX12 and make it go through the hole at the back of the head
![](img/assembly/XU4-hub-2.jpg)


## Continue the assembly

[You can go back to the general guidelines to continue the assembly.](head_assembly_instructions.md)
