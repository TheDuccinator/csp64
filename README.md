# CSP64

Command Stream Player for the c64

CSP64 was going to be the framework behind the C64 SID export found in Furnace in version 0.7.

At the moment, it does not do much. Right now, it's just the framework for the driver it will use but no actual SID playback has been done.

## How This Doohickey Works

1. CSP64 starts with compilation of the script for editing and packing FCS (Furnace Command Stream) files.
    - It has not been made yet...
2. Then, the script is executed. It does the aforementioned packing of FCS files, but it also assembles the source code (it has to be modular for Furnace, coming later) to a PRG file, and the FCS file is
inserted at `$1000`.
3. This `.prg` file is loaded and executed in your emulator (or real hardware) of choice. It plays the music, along with providing some visual feedback (but only in the `.prg`, not any other format).


## Disclaimer

This is a fork of a repo. This is not originally made by me.
