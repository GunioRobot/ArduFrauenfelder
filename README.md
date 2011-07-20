ArduFrauenfelder
=============================
Copyright 2011 Design Tech Industries (DTI)  
DTI site:  <www.mirrorshades.gs/DTI>  
DTI email: <admin@mirrorshades.gs>  

The ArduFrauenfelder is an Arduino compatible custom board with 
stepper motor drivers, running grbl.

Features:

 * ATmega328 MCU
 * SparkFun EasyDriver v4.4
 * Power LED & Reset switch
 * Populated pins for USB-to-TTL board
 * Mounting holes

You can view more at the ArduFrauenfelder page:

  http://mirrorshades.gs/DTI/ArduFrauenfelder/

The "docs" folder within this repository includes a handy copy of the
schematic in PDF format and images of the pcb.

In this repository you will find the project (.pro), netlist (.net), 
board (.brd) and schematic (.sch), along with a grbl file configured for the board.

**At the moment there is only the project, schematic and netlist as it is an ongoing 
endeavor to create the board file satisfactorily. If you can help in this regard please 
contact me, as well as if you find something that needs correction**

INSTALLATION
------------
The design is saved as a Kicad project. Kicad is an open source PCB design suite and is
free and available from http://kicad.sourceforge.net/. To use this project download it and 
place the directory containing these files into any directory on your computer. Then open 
Kicad and click file -> open then navigate to the directory where you saved the files, then 
open ArduFrauenfelder.pro (which is the Kicad project file).


DISTRIBUTION
------------
The specific terms of distribution of this project are governed by the
license referenced below.


LICENSE
-------
This work is licensed under the Creative Commons Attribution-ShareAlike License.  

To view a copy of this license, visit:

  http://creativecommons.org/licenses/by-sa/3.0/  
  http://creativecommons.org/licenses/by-sa/3.0/legalcode

or send a letter to

  Creative Commons  
  171 Second Street, Suite 300  
  San Francisco  
  California, 94105  
  USA

The "license" folder within this repository also contains copies of the
licenses referenced above.


CREDITS
-------
The ArduFrauenfelder was designed by Jamie Johnston (james-kun@mirrorshades.gs) 
based on previous work by the Arduino team (www.arduino.cc/playground/Main/People) 
which includes:

 * Massimo Banzi
 * David Cuartielles
 * Tom Igoe
 * Gianluca Martino
 * David A. Mellis
