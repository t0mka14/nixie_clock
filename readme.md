# Six digit nixie clock

I got my hands on handful of different nixie tubes when we were moving out some old wardrobes at CTU. I thought
this would be just a small project, but well... Anyway it turned out to be a max 6 digit (+2 dividers)
USB powered nixie clock. It is controlled by RP2040.

## Table of Contents
- [Z570M socket](#z570m socket)
- [HV power supply board](#hv-power-supply)
- [Digits and HV5530 board](#digits-and-HV5530-board)
- [Control board](#control-board)

### Z570M socket
This pcb is just a socket for the [Z570M](https://www.tube-tester.com/sites/nixie/data/z570m/z570m.htm).
There were original plastic sockets produced for them, but I don't have one. When soldering the tube, it is better
to cool down the contacts near the tube to avoid possible vacuum leak. It can be done with a wet napkin, just
be careful to not dissolve the red coating.
![Z570M pcb](/img/z570m.jpg)

