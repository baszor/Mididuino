# Midi-duino
A midicontroller based on an arduino nano

The original code can be downloaded from https://drive.google.com/file/d/0BwnVMB_6yujwR1dydVJ6MHJib2M/view
This code is written by Dave from notes and volts @ https://www.notesandvolts.com 
Watch his youtube movies to make your own version of a midi controller.

After toying around on a breadboard and converting this to a solder strip board.
I got annoyed by the prototyping process and started designing a PCB for it.
This project is the result :)

The arduino you click or solder on this board uses the script you can find on this page in the MIDI_controller folder.
It is a configured version of daves original code to fit two multiplexers that read 16 potentiometers.

To make the code work (compile) in the arduino IDE you must install the midi library files.
You can find these at https://github.com/FortySevenEffects/arduino_midi_library/releases/tag/4.2

Notes for soldering:

Solder the parts in the order from small to large.
Solder the two pinheader sockets in the top holes at the back of the board, leaving the two holes open at the bottom,
(when looking at the board in such a way so the printed R potmeter values are in normal reading order)
So that the arduino can be clicked into the sockets at the back of the board. See the images folder for reference pictures.

Din plug pinout (see pinout image in pcb image folder)

Connect pin 1 of the jumpers with pin 5 of the din plug (signal).
Connect pin 2 of the jumpers with pin 2 of the din plug (ground).
Connect pin 3 of the jumpers with pin 4 of the din plug (5v).
