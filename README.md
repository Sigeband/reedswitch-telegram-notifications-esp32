# Overview

This project utilizes and esp32 and to send an message over telegram if a door or window opens/closes.
It works with detecting if a connected reed-switch is closed or not,and then sends a message acordingly.




## Pinout:

![image](https://user-images.githubusercontent.com/114338337/215847824-6a8d162c-2f7a-4fb1-961a-24563dd50137.png)

## Materials:

```
1x ESP-32 NMCU (Can be any esp32)
1x 10K resitor
4x M2x12 flathead screws (for the case)
```

## Steps

```
1. Create a bot using botfather over telegram.(and copy the token)
2. Get your chatid via the myid bot.(and copy it)
3. Search for your bot,and klick start, else the bot wont be able to send you messages!
4. Add the token, and  chatid to the code.
5. Now add your wifi information.
6. Wire everything according to the "Pinout" section
7. Flash the code.
8. It Works!

9. if it doesnt, check the serial monitor and the code to see whats wrong / where its getting stuck.)

10. Still doesnt work? reach out to me, *maybe* i can help.
```

## 3D-Printing / Recommended Settings 

The case is designed to keep the esp32 safe, while still allowing a usb connection.
On the left side of the design you can see a small "tunnel" for the wires to pass through.
The case is designed to fit an nmcuesp32 with headers and the resistor.

*Recommended settings:*

```
0.28 layer height
40% infill 
3 walls
PLA/PETG/ABS (NO TPU)
Textured PEI sheet (for the looks)
```

