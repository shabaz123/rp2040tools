# rp2040tools

This repository contains a pre-built Windows x64 version of OpenOCD built for the Pi Pico (built using the instructions in the Pi Pico user guide).
This version of OpenOCD was built on 28th September 2022.

The repo also contains a pre-built version of Picoprobe, intended for Seed XIAO RP2040. It is the same as the normal Picoprobe build, except that the UART pins are on GP0/GP1, instead of GP4/GP5. The Seed XIAO board doesn't have GP4/GP5 broken out, so instead GP0/GP1 can be used. If you are not interested in using the UART capability of the Picoprobe, then you could just use the normal Picoprobe firmware, instead of the one in this repo. Also, the XIAO Picoprobe code was slightly altered to make use of the multi-color LED which is on the XIAO board. It is a bit bright however!

