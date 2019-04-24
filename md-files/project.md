***FabZero Project***           
------------------------------------------------------------------------------------------------------------------

![slide](/img/p1.png)

***Description:***    
*iBELL is an Intelligent BELL. It is a normal electronic BELL programmed to behave intelligent role. Whenever anybody misuses or tries to fool, it goes to "freezing mode" and gets activated after specified time. ie, If you press the switch and hold for more time its automatically switched to "Freeze Mode". Also, if anybody repeatedly presses the switch it enters to "Freeze Mode". Like this, several cases of events are worked out and programmed to behave intelligently.*

***PCB Design:***  
*The Circuit design, Schematic diagram, extraction of trace and cut files are detailed discussed in in the [***Fabzero Documents***](/md-files/fabzero-docs.md) menu and cutting is done using the Micro miller which is described in detail in the [***Fabzero Documents***](/md-files/fabzero-docs.md) menu under Micro miller.*

![schematic](/img/p2.jpg)   
![layout](/img/p3.jpg)    
![inkscape](/img/p4.jpg)    
![trace](/img/p5.jpg)    
![milling](/img/p6.jpg)   
![pcb](/img/p7.jpg)

***Implementation:***   
*Now, the components are soldered as per the PCB design on the circuit board. We have arrived at two circuit boards, one is the micro controller circuit and another one  is the MOSFET connected to the speaker. We have also used additional 2 nos.of 50ohm resistors connected in parallel to suppress the generated heat. Oscilloscope was used to verify the working functionality of the speaker.*

***List of Components used:***  
- *Resistors--500 ohms: 4 Nos.*  
- *Resistors--10 ohms: 2 Nos.*  
- *LED : Green & Blue -Each 1 No*   
- *Micro Controller -- ATtiny 44: 1 No.*   
- *Capacitor-- 1 Micro Farad : 1 No.*      
- *Switch: 1 No.*   
- *ISP Header: 1 No.*  
- *Speaker: 1 No.*    
- *Mosfet: 1 No.*

![pcbsoldering](/img/p8.jpg)  
![pcbsoldering](/img/p9.jpeg)   
![pcbtesting](/img/p10.jpg)

***Coding:***   
*AVR program was written as per our requirement. Through the programmer, using Arduino, we have compiled and successfully loaded the AVR code in to the micro controller to work intelligently as per our requirements.*

![coding](/img/p11.png)   
![coding](/img/p12.png) 

***3D Design for iBELL Outer Case:***   
*The 3d iBELL outer Case was designed using freecad software and the same was  loaded in to 3D printer. After 28 minutes, we are ready with the outer Casing for iBELL.
Now we have packed all the iBELL components inside the 3D case…*

![case](/img/p13.jpg)

***Vinyl Name sticker for iBELL:***   
*iBELL name sticker was designed using the inscape and cut it through the Vinyl cutter. We got a beautiful name sticker, which was stuck at both sides of the iBELL case.*

![namesticker](/img/p14.jpg)

***Future Enhancement:***   
*iBELL has vast scope for future enhancement.
Intelligence can be fed to iBELL in the form of uploading program one by one on case basis, so as to behave more intelligently with added features/functionalities.*  
- *Case 1, if switch is pressed and held for more time, iBELL goes to freezing mode (inactive mode) and after sometime automatically turns to active mode.*
- *Case 2, if switch is pressed on and off frequently within the particular time interval, again it goes to freezing mode and turns to active mode after some time.*   
- *Case 1 & 2 events happen when a known person is trying to fool us. In this circumstance, iBELL acts intelligently by going to inactive mode temporarily.*   
- *Case 3, iBELL can be enhanced to work like an Access Control system. List of known users face images and finger prints can be saved in the database. A camera and finger print capturing devices can be attached to iBELL. When any person presses the switch, immediately it matches the face and finger prints with the stored database and based on the access permissions it automatically signals the access door to lock or unlock. This feature will be very helpful for persons living in the same family (children/husband/wife/father/mother/sister/brother). They need not wait for the family person to wake up and come to open the door.*   
- *Case 4, Even we can program iBELL to sound the names of the person standing behind the door.*   
- *Case 5, In sensitive areas (Border areas, LoC) iBELL can be attached to the CCTV camera, so that it alarms loudly and sends MMS messages / videos automatically to the control room, if anyone tries to enter with unauthorized / heavy weapons /materials.*   

*Like this we can keep on loading iBELL with updated programs for latest features and requirements.*


![tankyou](/img/tq.jpg)

[***Home***](/README.md)












