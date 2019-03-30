***PCB Design & Miller Cutter***  
*Design the Schematic circuit and draw the PCB layout was performed by KiCAD software and we used the DGSHAPE SRM20 model miller cutter machine for mill PCB board.  
The SRM-20’s VPanel controller provides a simple interface for adjusting tool position and moving the cursor to set the milling starting point. The VPanel also allows easy control of feed rate and spindle speed with pause and resume operation, plus tracking of X, Y, Z axis milling with a numeric readout in millimeters or inches.*  
*This machine has 2 milling bit. One as tracebit for tracing the circuit in board (i.e 1/64) and another one as cut bit for cut the board(i.e 1/32)* 
![SRM20](/img/srm20.jpg)    
**Procedure for design the circuit:**  
- *Open KiCAD software and load new project*  
- *Select Schematic layout, then Eeschma will be open*  
- *Load the components, Vcc and GND from the place symbol icon. Add the required components from the symbol library.Type of components may very as per the availability at the LAB*  
- *After selecting the components fix the connection using place wire symbol.Then, Use **NO Connection** flag for unused pins/connections.*  
- *After completion of circuit, Annotate schematic symbols for un-named components*  
- *Then,perform electrical rules check for clear all the errors if any.*  

![Schematic](/img/schematic.jpg)

- *Assign PCB footprints to schematic symbols as per the fablab availability and generate net list.*  
- *Run PCBnew to layout pcb. Now schematic circuit convert to PCB layout.*  
- *PCBNew circuit opened in new window for create layout. In this window, hit the "update pcb from schematic" button .Then the the pcb layout will appear in the screen.Align the components within the layout and replace connecting white lines by route tracks.*  
- *Use add graphics line button for draw the edge cut layer (i.e outer yellow line)*  

![pcblayout](/img/pcblayout.jpg)

- *Then, select the plot format as svg and tick the check box of Exclude pads from silkscreen, negative plot and zones fills before ploting. Rest of things uncheck.*  
- *Now, 2 nos of .svg format files created and it'll open through inkspace. Select the files and set dpi as 2000 and export as .png format.* 

![inkscape](/img/inkscape.jpg)

- *Open the .png files in fabmodules.org and select the .png file in input. In the output format choose .rml format.And the process, select PCB trace(1/64) for pcb trace and PCB cut(1/32) for cut file.*      
- *Under output, select machine as SRM 20 and fix 0 for X,Y and Z.Remains all default.Now press calculate and save the files as .rml format. Repeat the process for cut file and invert.* 

![fabmodule](/img/fabmodule.jpg)

**Procedure for Milling the PCB**  
*Milling the circuit board is performed by the VPanel toolbar in the SRM20 Machine.*
![SRM20-panel](/img/srm20-panel.jpg)
- *First, fix the 1/64 milling bit into the machine for printing the circuit/trace in the on the PCB.*
- *Approximately  move the X & Y in the V-Panel and move the PCB board to inside the machine.*
- *carefully loose the bit and touch the PCB platform and tight the bit. Set the Z at Zero(0) and move X,Y axis to the exact position for starting point of circuit by adjusting the Z axis.Then, this position set the X,Y,Z to zero.*
- *Using cut option in Vpanel, load the trace file in .rml format and hit the output tap in the Vpanel.Now the machine will be printing/milling the circuit on PCB.*
![pcbmilling](/img/pcbmilling.jpg)
- *Once the milling of trace is completed, the bit to be changed in 1/32 for cut the PCB.*
- *After replace the bit, change the Z axis as zero and similar to the tracing setup make X,Y axis to the previous setup starting point.*
- *Then, load the cut file as the .rml format and proceed to cut the PCB.* 

![pcb](/img/pcb1.jpg)

- *After completion of above process remove the printed PCB carefully.*

![finalpcb](/img/pcb2.jpg)

- *Then collect the necessary components according to out circuit and soldering in to the PCB.*
![solderingpcb](/img/solderingpcb.jpg)