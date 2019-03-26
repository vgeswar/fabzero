*Design the Schematic circuit and draw the PCB layout was performed by KiCAD software and we used the DGSHAPE SRM20 model miller cutter machine for mill PCB board.  
The SRM-20’s VPanel controller provides a simple interface for adjusting tool position and moving the cursor to set the milling starting point. The VPanel also allows easy control of feed rate and spindle speed with pause and resume operation, plus tracking of X, Y, Z axis milling with a numeric readout in millimeters or inches.*  
*This machine has 2 milling bit. One for tracebit (i.e 1/64) and another one for cut bit(i.e 1/32)* 
![SRM20](/img/srm20.jpg)    
**Procedure for design the circuit:**  
- *Open KiCAD software and load new project*  
- *Select Schematic layout, then Eeschma will be open*  
- *Load the components, Vcc and GND from the place symbol icon. Add the required components from the symbol library.Type of components may very as per the availability at the LAB*  
- *After selecting the components fix the connection using place wire symbol.Then, Use **NO Connection** flag for unused pins/connections.*  
- *After completion of circuit, Annotate schematic symbols for un-named components*  
- *Then,perform electrical rules check for clear all the errors if any.*  
- *Assign PCB footprints to schematic symbols as per the fablab availability and generate net list.*  
- *Run PCBnew to layout pcb. Now schematic circuit convert to PCB layout.*  
- *PCBNew circuit opened in new window for create layout. Align the components within the layout and replace connecting white lines by route tracks.*  
- *Use add graphics line button for draw the edge cut layer (i.e outer yellow line)*  
- *Then, select the plot format as svg and tick the check box of Exclude pads from silkscreen, negative plot and zones fills before ploting. Rest of things uncheck.*  
- *Now, 2 nos of .svg format files created and it'll open through inkspace. Select the files and set dpi as 2000 and export as .png format.*  
- *Open the .png files in fabmodules.org and select the .png file in input. In the output format choose .rml format.And the process, select PCB trace(1/64) for pcb trace and PCB cut(1/32) for cut file.*      
- *Under output, select machine as SRM 20 and fix 0 for X,Y and Z.Remains all default.Now press calculate and save the files as .rml format. Repeat the process for cut file and invert.* 

**Procedure for Milling the PCB**  
*Milling the circuit board is performed by the VPanel in the SRM20 Machine.*
![SRM20-panel](/img/srm20-panel.jpg)