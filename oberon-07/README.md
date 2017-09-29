aenig4 - Enigma M4 Cipher Machine Emulator (Oberon-07 version)
==============================================================

`aenig4` emulates the Enigma M4 cipher machine used by the U-boot division of
the German Navy during World War II. It can be used as well to emulate the
Enigma I machine (M1, M2, M3).

This version of the program is written in the Oberon-07 language as designed by
Niklaus Wirth, and is a port of the original - and supported - version,
programmed in C, and all the documentation, configure and install scripts can
be found at http://jorgicor.sdfeu.org/aenig4 .

This is free software. See the file `COPYING` for copying conditions.

Copyright (c) 2017 Jorge Giner Cordero

Compiling
=========

You need the OBNC compiler by Karl Landström. It can be found at:

http://miasap.se/obnc/

Moreover you need the obnc-libstd library at the same location.

To compile the program, either run `obnc aenig4.obn` or type `make`.
