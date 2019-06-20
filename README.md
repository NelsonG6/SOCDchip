
# Game controller direction input filter

![Breadboard](https://github.com/NelsonG6/SOCDchip/blob/master/Images/breadboard%20example.png?raw=true)
- Help with the design came from the PSU [electronics prototyping lab](http://psu-epl.github.io/)
- The concept of the chip is to provide game controllers with a ruleset for how left+right is handled, and up+down.
- The chip takes an input for each of the 4 directional buttons, and passes out a filtered input that goes into the pcb.
- A 5v power source is required to power the logic chips, and a ground wire.
