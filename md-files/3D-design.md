***3D Design & Printing***  

*Our mentor instructed to us design something useful for our lab. So my batch consists of three members decided to design the Bit-Stand for holding the pcb milling bits. In this process we are using [**FreeCAD**](https://www.freecadweb.org/) software for perform the 3D design. FreeCAD is a popular open source design software for creating 3D models of real-life objects.* 

***Scope of Work***   
To design a 3D model for holding the Micromiller bits. We designed a small block( Length: 30mm; Width: 50mm; Height:25mm) containing 5 cylindrical cut of radius 2mm  that can properly accommodate 5 Micromiller bits

![Bitstand](/img/3D-design.jpg)

*The procedure of our assignment is following:*  
- *Open FreeCAD and create a new empty document and select part option from the "**software between workbenches**" option.*
- *Pick a cube set and set the dimension of Lenth-30mm, Width-50mm and Hight-25mm.This is the base for the Stand.*
- *Copy and paste another cube as the dimensions of Lenth-40mm, width-13.5mm and Height-15mm and move it to center of the base in X,Y and move on the top of the base cube through Z axis.*
- *Select the top cube's edges and opted the fillet button and applied the fillet and repeat the same for another cube also.*
- *Select the boolean operation for make the union of two fillets.*
- *Now, pick a cylinder and set the size radious-1.75mm, hight-50mm. The dia of bit is 3mm. In order to fix the bit stand radious of cylinder is 1.75mm.*
- *Move the cylinder n Z axis for 10mm & Yaxis for 14.2 mm in the center of cube 2.*
- *Now create 2 more cylinder at the same size and position of above cylinder*
- *Move first cylinder to 10mm of X axis and move cylinder-2 in 20mm and third in 30mm of X axis.*
- *Run a boolean operation for difference between fussion & cylinder-1. A cut will be created. Another boolean difference between cut and cylinder 2.Now cut-1 will be created. Similarly, another boolean between cut-1 and cylinder-3.Repeat the same process up to cylinder-5. The resulting product is given below:*

![Bitstand](/img/bitholderdesign.jpg)


- *Save this file as .FCStd format and export the same as .stl format.*
- *Now .stl format opened in 3Dwox software of Sindoh 3D printer and load the file.*
- *Use rotate option to align it for proper position.*
- *Now click layer viewer option to check the layered view and verify the support is requirements. If support is required provide the same from setting options.*
- *Now give print to the Sindow if connected.Else save it as .Gcode format in USP and give print the file by the connecting USB in the printer.*

*The final output of the product is given below:*

![Bitstand](/img/bitholder1.jpeg)

![Bitstand](/img/bitholder2.jpeg)

[***Back***](/md-files/fabzero-docs.md)  

[***Home***](/README.md)

