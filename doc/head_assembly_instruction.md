# Face Assembly

This page will guide you through the process of assembling the head of your Poppy.

## STEP 0:

Ensure you have all components required in the [Bill Of Materials](BOM.md)

**Fixings:**
- 2x Wrench Bolt M2.5*4
- 2x Wrench Bolt M2.5*6
- 1x Screw M3
- 14x Screw M2x5mm
- 10x Nut M2.5
- 16x Nut M2

## Step 1: Put hex nuts in the head face

Prepare the *head_face* part for assembly by putting all hex nuts as indicated in the following illustration:

You may have to use a small screwdriver or a pliers to help you *clip* nuts inside holes.

![](img/assembly/head_front_nuts.jpg)

## Step 2: Put the screen

Now, you can assemble the screen on the *head_face* following the different steps below:

![](img/assembly/head_face_all_parts.jpg)

![](img/assembly/head_face_step_2.jpg)

![](img/assembly/head_face_assembly_step_2.jpg)

To fix the *manga screen* or the *3D printed fake screen*, use 2x M2.5x6mm bolt:

![](img/assembly/head_face_screen_assembly.jpg)

![](img/assembly/head_face_assembled_back.jpg)

You should obtain this !

![](img/assembly/head_face_assembled_front.jpg)

## Step 3: Add the camera
First you have to put 3x hex nut M2 in the hex holes of the *camera_support* part:
![](img/assembly/camera_support_nuts.jpg)

Then you can assemble the *support_camera* part on the *head_face* with 2x **M2x4mm bolt (/!\ if you use longer bolt it may go through the head and create holes on the front side...)**:

![](img/assembly/head_face_camera_support_parts.jpg)

With 3 M2x5 screws, you can fix the camera on the *support_camera* part:
![](img/assembly/head_face_camera_parts.jpg)

![](img/assembly/head_face_assembled_camera_back.jpg)

And you got your Poppy with the camera !
![](img/assembly/head_face_assembled_camera_front.jpg)


## Step 4: Add the speakers

For fixing speakers, there are two different 3D parts, one for the right side and one for the left side. Don't worry, it's written on each part.

![](img/assembly/audio_parts.jpg)

![](img/assembly/head_face_audio_step_2.jpg)

Use 2x M2x5mm screws to fix each speaker:

![](img/assembly/head_face_assembled_audio.jpg)


## Step 5: Assemble the motor with the head_back

Take 6 M2 hex nuts and put them on the Dynamixel AX-12 as shown on the next photo:
![](img/assembly/head_motor_nuts.jpg)

Then you need 6 M2x5 screws to fix the motor with the head:
![](img/assembly/head_back_motor_parts.jpg)

Beware of putting the AX-12 in the correct position:

![](img/assembly/head_back_motor_step_2.jpg)

Then fix the motor using the 6 screws. Do not forget to use threadlock if you want to keep your Poppy in good condition.
![](img/assembly/head_back_motor_assembled.jpg)


## Step 6: assemble the electronics in the head

For the next step, there are currently two versions depending on the computer you are using leading to 2 differents *head_back* part. Choose the one you have to continue the assembly process

![](img/assembly/diff_U3-XU4.jpg)

- [You have the version with Odroid U3 >>>](head_back_U3.md)
- [You have the version with Odroid XU4 >>>](head_back_XU4.md)


## Step 7: assemble the head with the body
Either you have an Odroid U3 or XU4, this step is similar.

Take the body and the head of your Poppy:
![](img/assembly/XU4-head-assembly-1.jpg)

Put the head motor on the neck (U shape part), align the mark to ensure the initial position is correct:
![](img/assembly/XU4-head-assembly-2.jpg)

Use 4x M2x5 screws to assemble the motor with the neck (use threadlock):
![](img/assembly/XU4-head-assembly-3.jpg)

Turn the neck and fix the other side with the big Robotis screw M3 (use threadlock).
![](img/assembly/XU4-head-assembly-4.jpg)

Close the head gently and take care all wires fit inside.
![](img/assembly/XU4-head-assembly-5.jpg)

Use 3 long M2 screw to assemble the back and the face together:
![](img/assembly/XU4-head-assembly-0.jpg)

There is 3 holes, one on each side and one on the top.
![](img/assembly/XU4-head-assembly-6.jpg)

## Step 8: Connect the head to the electric circuit

On both version (U3 & XU4), to connect the Poppy's head with the body, you have to:

- connect the 2 ways power wire (5V) with a 4 pins connector to the upper body SMPS2Dynamixel.
- connect the short 3 ways wire (coming from one of the USB2AX) to an available 3 pins slot at the base of the neck.
- connect the long 3 ways wire (coming from the second USB2AX) to an available 3 pins slot on the pelvis.
![](img/assembly/U3-head-assembly-11.jpg)

On the XU4 version, you have in addtion to plug the jack connector on the Odroid port.

![](img/assembly/XU4-head-assembly-7.jpg)
