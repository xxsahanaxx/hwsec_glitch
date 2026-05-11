<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project incorporates AES-encryption on a chip, that can be glitched and obtained using some methods of Trojan detection.  

## How to test

In order to test our project, we must have a main PCB that connects the chip to multiple peripherals, and have ports/jumpers for side channels. 

On top of these requirements, we also have oscilloscopes and debug probes such as JLink to help identify the glitch.

## External hardware

For the purposes of this project, we use the Hackster board designed by my supervisor to inject glitches onto the PCB.