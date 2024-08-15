# rp2040tools

This repository contains a pre-built Windows x64 version of OpenOCD built for the Pi Pico (built using the instructions in the Pi Pico user guide).

There are zip files containing versions of OpenOCD built on the following dates (but use the most recent, unless there's a specific reason not to!):
~~~
19th May 2024 (this version was tested with both Pi Pico and Xiao RP2040)
14th Oct 2023
28th September 2022
~~~

The repo also contains a pre-built version of Picoprobe, intended for Seed XIAO RP2040. It is the same as the normal Picoprobe build, except that the UART pins are on GP0/GP1, instead of GP4/GP5. The Seed XIAO board doesn't have GP4/GP5 broken out, so instead GP0/GP1 can be used. If you are not interested in using the UART capability of the Picoprobe, then you could just use the normal Picoprobe firmware, instead of the one in this repo. Also, the XIAO Picoprobe code was slightly altered to make use of the multi-color LED which is on the XIAO board. It is a bit bright however!

The repo also contains a pre-built version of picotool v2.0.0, built for Windows 11. 
