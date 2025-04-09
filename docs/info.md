<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This is just some basic logic gates:
+ OUT0 is output of MUX, S is output of INV I0, I0 is output of IN1 AND IN2, I0 is output of IN3 OR IN4
+ OUT1 is INV of IN0
+ OUT2 is IN1 AND IN2
+ OUT3 is IN3 OR IN4
+ OUT4 is IN5 XOR IN6
+ OUT5 is output Q of DFF, D is output of IN5 XOR IN6, CLK is IN7
+ OUT6 is output Q_not of DFF, D is output of IN5 XOR IN6, CLK is IN7
+ OUT7 is output of IN7

## How to test

Change input switches, watch how output leds change

## External hardware

Switches for input, leds for output
