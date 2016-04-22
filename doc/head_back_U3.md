# U3 version assembly

## Step 0: Wiring
Before starting, verify you have followed the steps explained in the [wiring documentation](wiring.md) concerning the audio and power connections.

## Step 1: Connect the audio amplifier
The jack connector is near the ethernet connector, you need to plug the jack before fixing the board because it won't be accessible afterward.
![](img/assembly/U3-head-assembly-5.jpg)
![](img/assembly/U3-head-assembly-6.jpg)

## Step 2: Fix the Odroid U3 in the head
Here you have a simple view *(without audio)* of the way to position and fix the Odroid U3 board to the *head_back* part.

You need to put 2 hex nuts on the hex holes and use 2 M2.5x8mm bolt to screws the U3 at its place.
![](img/assembly/U3-u3-2.jpg)

## Step 3: Connect cables

You have now to plug the USB devices. There are 3 availables port on the odroid. If you want both wifi and camera please add a small usb hub.
![](img/assembly/U3-hub-1.jpg)

- plug all usb devices
- connect the long 3 ways cable to one of the USB2AX and make it go through the hole at the back of the head
- connect the shorter 3 ways cable between the 2nd USB2AX and the Dynamixel AX12
- connect a 20cm 3 ways cable to the Dynamixel AX12 and make it go through the hole at the back of the head
![](img/assembly/U3-hub-2.jpg)

### Step 4: Connect the power of the Odroid

After doing step 1, 2 and 3, you should obtain something similar to this:
![](img/assembly/U3-head-assembly-7.jpg)

Plug the small power jack to the odroid U3:
![](img/assembly/U3-head-assembly-8.jpg)
