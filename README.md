# LA-HOULE
<B>LA HOULE is about additive synthesis and many waves.</B> It is the adaption of TIDES in Serge compatible format.

Mouser cart: https://eu.mouser.com/ProjectManager/ProjectDetail.aspx?AccessID=ee024b02ed

Firmware update procedure

Unplug all CV inputs/outputs from the module. Connect the output of your audio interface/sound card to the FM input. Power on your modular system with LA HOULE mode switch pressed. The 3 LEDs will blink, with a yellow color.

Make sure that no additional sound (such as email notification sounds, background music etc.) from your computer will be played during the procedure. Make sure that your speakers/monitors are not connected to your audio interface - the noises emitted during the procedure are aggressive and can harm your hearing. On non-studio audio equipment (for example the line output from a Desktop computer), you might have to turn up the gain to the maximum.

When you are all set, play the firmware update file into the module. The LEDs show a cyclic pattern and periodically flash green upon receiving a valid block of data. The unit reboots after the last packet has been received.

In case the signal level is inadequate or too high, the procedure will stop and all 3 LEDs will be lit in red. Try adjusting the output level, press the mode button and retry from the start of the update file.

Calibration procedure
To calibrate the unit:

- Disconnect all CV inputs.
- Connect the note CV output of a well-calibrated keyboard interface or MIDI-CV converter to the V/OCT input. Leave all the other CV inputs unpatched.
- Press both buttons and simultaneously. The first LED slowly blinks in orange.
- Send a voltage of 1.000V to the V/OCT input.
- Press any button. The second LED blinks in orange.
- Send a voltage of 3.000V to the V/OCT input.
- Press any button.

Easter egg

- Patch dummy cables to the FM and LEVEL inputs to disable the internal normalization.

- Press the top button (mode, labelled A in the manual) for one second. All LEDs light up in yellow.

- Press the top button again for one second. All LEDs light up in green.

- Press the bottom button (range, labelled B in the manual) for one second. All LEDs should light up in red.

An oscilloscope in X-Y mode will show a drawing of a pair of peacocks when visualizing the UNI and BI outputs.
