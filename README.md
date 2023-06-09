# messedup-diy
DIY Build Instructions for Messed Up
![](img/IMG_3441.png)

Your kit should contain:

- 1 PCB layer 1
- 1 PCB layer 2
- 1 Messed Up aluminum face panel
- 1 2x5 2.54mm pin header
- 2 2x6 2mm locking pin headers
- 2 2x6 2mm locking pin sockets
- 1 2x6 2mm right-angle pin header
- 4 digit 7 segment display
- 1 2x8 2.5mm IC socket
- 2 SPDT toggle switches
- 2 pushbutton switches
- 2 pushbutton encoders
- 1 9mm D-shaft potentiometer
- 1 9mm trimmer potentiometer
- 10 PJ398 jacks ("Thonkiconn")
- 10 jack nuts
- 5 green LEDs
- 2 yellow LEDs
- 2 skirted encoder knobs (with caps)
- 1 unskirted potentiometer knob (with cap)
- 1 trimmer cap
- 1 ribbon cable

```
In early kits, the rear PCB panel (the little one) may come
pre-assembled.
```

## Building

### 1. Interconnect pin sockets.

In some of our earlier kits, the rear PCB will come pre-assembled, so you can skip this step.

Start with the smaller PCB and the two white pin sockets.

![](img/IMG_3442_comb.png)

Both sides have a thin ridge in the plastic casing, but only one side has two thin lines in the ridge.

The pin sockets are locking, and have polarity. Those thin lines must fit into the black shrouded headers in step 3.

Make sure the side with the two thin lines is facing towards the top of the PCB, where the USB connector is located.

![](img/IMG_3444_combo.png)

### 2. Display pin sockets.

For the display, we use a 16-pin (2x8) IC socket.

Since the display is wider than a normal IC, break it in half first. Be careful not to break it too quickly or forcefully, or the part with pins might break too.

![](img/IMG_3452_comb.png)

![](img/IMG_3454.png)

### 3. Interconnect pin headers.

Next, take the two black shrouded pin headers.

![](img/IMG_3455.png)

To ensure they fit correctly, connect them to the bottom board before soldering.

![](img/IMG_3457.png)

![](img/IMG_3459.png)

### Optional: Solder the power header.

If you want, you can solder the power header (J13).

However, we usually wait to the end, since the header can get in the way.

![](img/IMG_3486.png)

### 4. Place the display in the socket.

But if you're worried about damaging it, wait until you've finished everything else.

![](img/IMG_3460.png)

### 5. Fit the pushbutton switches.

These switches include an LED, which has a polarity.

The pin marked in green is the cathode of the LED. Follow the markings on the silkscreen to place it correctly.

The switches should stay in place on their own. But you can solder one pin to hold them in place.

![](img/IMG_3461_combo.png)

### 5. Prep the pot and encoders.

First, remove any washers and nuts.

On the potentiometer, use a pair of pliers to trim off the small stability pin on top. Make sure it's entirely removed, so the panel can sit flat against the pot. Otherwise it can cause other components to be mis-aligned.

The encoders have stability pins too, but they don't need to be removed.

The small trimmer pot has no nut, washer, or stability pin.

![](img/IMG_3464.png)

![](img/IMG_3469.png)

### 6. Fit the pots, encoders, and toggle switches.

As with the buttons, you can solder one leg of each if you like.

However, do not solder all pins until later (when the panel is added), or they could turn out very crooked.

![](img/IMG_3470.png)

### 7. Fit the jacks.

This part can be a little tricky, because the jacks fit loosely. You might be tempted to solder a pin on each jack to keep them in place. Doing that will keep the jacks flush, but they can still be off-center. So it's best to avoid soldering them until the panel is added.

The two shrouded pin headers should allow you to lay the PCB flat on the table while you insert the jacks.

![](img/IMG_3471.png)

### 8. Fit the LEDs.

LEDs have multiple polarity markings. The flat side of of the casing marks the cathode. The shorter leg also marks the cathode. VERY rarely, an LED is made incorrectly and these don't line up. In that case, you'll need to look at the Anvil and Post inside the case/lens to confirm the polarity.

The cathode of the LED should be placed in the square hole on the PCB.

![](img/IMG_3477.png)

![](img/IMG_3473.png)

### 8. Fit the panel.

This is probably the hardest part of the build. To make sure that everything lines up perfectly, you want to fit the panel while all the components are still loose. To do this, keep the PCB and panel parallel to the ground. Place the panel over the components, and press down with your thumbs while holding the PCB in place with your other fingers.

Once the panel is at least partially in place, you should be able to hold the panel and PCB together with once hand. Then you can use your other hand to nudge all the components into place.

Once you do, add nuts for a few of the jacks and for the truncate potentiometer. This will be enough to hold everything in place.


The panel holes are a bit tight for the "round" and "free" toggle switches. Don't be afraid to use some force to push the panel into place. It should rest flatly across all the jacks.

![](img/IMG_3479.png)

![](img/IMG_3481.png)

### 9. Solder the controls and jacks.

With nuts fitted, you can flip over the PCB, allowing the LEDs to fall into place. Before soldering, make sure each LED has found its place.

![](img/IMG_3485.png)

### 10. Solder the power header.

Once everything is soldered, remove the nuts and the panel so you can solder the power header. The power header is a 2x5 2.54mm unshrouded pin header. We avoid shrouded power connectors because they provide false confidence: ribbon cables with backwards connectors aren't uncommon. Instead, our modules have clear markings and reverse-polarity protection.

It may seem counter-productive to fit the panel, then remove it. But the power header is longer than the shrouded headers, so it's harder to fit all the components when it's soldered, since the PCB won't lay parallel to the table/ground.

![](img/IMG_3486.png)

![](img/IMG_3487.png)

![](img/IMG_3488.png)

### 11. Fit the panel (again).

Now that the power header is soldered, you can fit the panel and add all the nuts. Make sure not to overtighten the nuts for the encoders. They're partly held into place by the mounting pins.

![](img/IMG_3489.png)

### 12. Fit the knobs.

The pots and encoders are D-shaft, so you simply need to press down on the knobs to fit them.

![](img/IMG_3495_combo.png)

### 13. Add the jumper.

If you have a very early version of Messed Up, you'll need to add this 2-pin header and jumper in order to program the module.

With your kit, we probably provided a right angle header. If you have a straight header, bend the pins so they don't press against the upper PCB.

![](img/IMG_3490.png)

![](img/IMG_3491.png)

![](img/IMG_3493.png)

![](img/IMG_3494.png)

### 14. Program the module.

```
If your rear PCB came pre-assembled, your chip was already programmed, and you shouldn't need to program it.
```

Using a personal computer, the RP2040 chip that powers Messed Up can be programmed by mounting the drive as a disk and dropping in a file. The `upload` folder contains the `firmware.elf` and `firmware.uf2` files. You should only need `firmware.uf2`, but the elf file is provided too, in case you want it.

1. Remove the rear panel from your Messed Up.
![](img/IMG_3540.png)
2. Find the Boot and Ground pins, and attach a jumper to pull Boot to Ground. Now when the device is powered on, it's ready for programming.
![](img/IMG_3541.png)
3. Connect the rear panel to Messed Up.
4. Connect the Messed Up module to your computer using a USB cable. The USB cable is for data only and won't power the module, so you won't see anything on your computer yet.
![](img/IMG_3542.png)
5. Connect the Messed Up module to 12v rack power. This can be a little tricky with the USB cable in place, but not too bad.
![](img/IMG_3545.png)
6. Now, with the rack powered, the RP2040 should mount as a drive.
7. Find the `firmware.uf2` file from the `upload` directory in this repository, and copy it to the mounted RP2040 drive. The drive should disappear after you copy over this file.
![](img/rpi-upload.png)
8. Unpower your Messed Up and disconnect the USB cable.
9. Remove the rear panel again and remove the jumper.
10. Connect the rear panel again. You're ready to power on Messed Up. At this point, everything should work correctly. You can verify that the display works, that the encoders change the value of beats and divide, and that the LEDs illuminate correctly. The last step is to calibrate the inputs.

## Calibrating

Once Messed Up is assembled, the last step is to calibrate the inputs. Messed Up needs to record the voltage reading of each input when nothing is corrected, in order to establish a zero volt baseline. To calibrate Messed Up, first make sure that nothing is connected to any of Messed Up's inputs. Next, with Messed Up powered off, hold down both the Beat and the Divide encoder. With both encoders held down, power on the module (this can be a little tricky). Once the module powers on, keep the encoders held down until you see the module display "CALI". Once that happens you can let go of the encoders. Power the module off and then restart it. If everything worked correctly, you should see the module display 07:04, which means that all of the inputs are reading zero volts.

Congratulations! Your Messed Up is ready.