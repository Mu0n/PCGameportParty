# PC Gameport Party

<img width="743" height="506" alt="pcgameportyparty" src="https://github.com/user-attachments/assets/5ff82125-ac48-49fa-a0e7-24b314e0a9af" />

## Description

The PC Gameport Party allows you to use your vintage PC’s gameport to its maximum use case scenario.
Instead of having separate cabling solutions that would allow:

* plug 2 joysticks at once 
* use MIDI out to a synth module 
* use MIDI in with a playing keyboard controller 

… it lets you do ALL of them at once. No more unplugging and replugging dedicated cables.

Want to support the PC Gameport Party project? Please raise an issue with known tested PCs (machines and sound cards).

You can donate via ko-fi: https://ko-fi.com/1bitfeverdreams

## Items you must secure yourself

* PC joysticks and/or PC gamepads
* DB15 cable M (goes into PC) to F (goes into the PC gameport party, this product here)
* MIDI cables, DIN5 variety

## Possible use cases for this project:

* Use a normal joystick on the player 1 socket
* Use a complicated flight stick with multiple analog axes and up to 4 buttons on the player 1 socket
* Use two normal joysticks on the player 1 and 2 sockets (must slide the switch to the 2 players mode)
* Play back MIDI music from your favorite early 90’s DOS/Windows games without sacrificing the usage of your joystick(s)
* Compose music in MS-DOS and windows sequencing programs

## Fabricate the PCB and BOM

These files are located in the /PCB/ directory:

* Build of Material (BOM) for LCSC part supplier normally used with JLCPCB (the contents are also listed in the table below)
* PDF schematics
* Gerber files for a black PCB and green PCB
* Pick and Place file

If you only want the PCBs without having the parts pre-assembled by a manufacturer, here is the build of material for LCSC:

| Name | Part | Quantity | Link | 
| ------------- | ------------- | ------------- | ------------- |
| MIDI DIN5 Socket | C2939344 | 2 | https://www.lcsc.com/product-detail/C2939344.html?s_z=n_C2939344 |
| 15P F DSUB | C77832 | 2 | https://www.lcsc.com/product-detail/C77832.html?s_z=n_C77832 |
| 15P M DSUB | C77837 | 1 | https://www.lcsc.com/product-detail/C77837.html?s_z=n_C77837 |
| 220 Ohm Resistor | C127220 | 4 | https://www.lcsc.com/product-detail/C127220.html?s_z=n_C127220 |
| Signal Diode 1A | C156296 | 1 | https://www.lcsc.com/product-detail/C156296.html?s_z=n_C156296 |
| 4-Pole Double Throw Switch | C388871 | 1 | https://www.lcsc.com/product-detail/C388871.html?s_z=n_C388871 |
| DIP Schmitt Trigger Photocoupler H11L1 | C78588 | 1 | https://www.lcsc.com/product-detail/C78588.html?s_z=n_C78588 |



## Buy it pre-fabricated

Currently, only one vendor is selling assembled PC Gameport Party boards. You may go that route if ordering a PCB or soldering the components yourself is not your personal preference.

Joe's Computer Museum (USA based): https://jcm-1.com/product/pc-gameport-party/

## Gameport general knowledge

Wikipedia page on the PC gameport: https://en.wikipedia.org/wiki/Game_port#Initial_IBM_PC_type_game_ports
This is an excellent external guide on the topic for MIDI on old vintage PCs: https://www.dosdays.co.uk/topics/pc_midi.php

## Known tested compatible scenarios

* IBM 486 DX2/66 with a Sound Blaster 16 vibra CT2940
* WeeCee with a crystal CS4237B sound chip that has a gameport tied to it (what's a WeeCee? https://www.youtube.com/watch?v=aJEp4ZUG7BI)

## License

The hardware portion of this repository are licensed under the CERN OHL version 2, permissive.
