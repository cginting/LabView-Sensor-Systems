# LabView-Sensor-Systems

ALL FILES MUST BE IN THE SAME FOLDER.

See IMG_0312 for a physical hardware setup. The setup will require 8 LEDs, 18 wires, a breadboard, a National Instruments MyDAQ, Labview software (2022 release), and a computer with a USB-B connection.

The objective of these programs are to create and implement various LED systems. The systems are digitally displayed in LabView, but phsyical displays can be made using a National Instruments MyDAQ.

460 proj alpha.vi: plays jingle bells.wav while displaying LED patterns. When the lead singer comes on, the LED pattern switches from choreographed lights to sound amplitude based lights.

recorder.vi: records keystrokes from keyboard into an excel file. Once a pattern is finished, press the spacebar to finalize the recording, then hit the stop button or the abort vi button.

player.vi: plays the exact pattern played by the user with additional controls. LED lights will glow in series in the front panel. The vi pulls data values from keyboardpatternBeta.csv. A Jingle Bells Rhythm is already installed. Making a new pattern will overwrite old patterns.

keyboardpatternBeta.csv: stores the times inbetween keystrokes

loadingpattern.vi: separate from the player and recorder programs. Produces a loading pattern where the LED bounces back and forth as the user directs. The default pattern will bounce an LED in the front panel between the 1st and 8th LED.
