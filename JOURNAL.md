# Journal

## Session One - May 8, 2026 (1 hour 49 minutes)
I began this project by creating a CAD model using OnShape. The goal was to create a mechanism that uses a DC motor to compress an Ambu Bag. 
I wanted the ability to control both how much compression is applied to the Ambu Bag, as well as how fast the bag is compressed. This allows me to control both the volume of air and the BPM of the ventilator. 
By the end of my first CAD Session, I had created the system to hold the Ambu Bag in place, as the mount for the motor, and the start of the mechanism. 
My choice of parts (a CIM motor, a 12"x7" polycarbonate sheet, etc) was based on the parts that I already had on hand.

<img height="250" alt="image" src="https://github.com/user-attachments/assets/f1637e09-1765-4752-b1b5-d84cf2ac6404" />
<img height="250" alt="image" src="https://github.com/user-attachments/assets/7be9dd56-5bf8-4523-8055-ce1e7ebe250e" />
<img height="250" alt="image" src="https://github.com/user-attachments/assets/d1da7e8d-4d02-4af8-a249-1516756316a2" />

Progress by the end of Session One

## Session Two - May 9, 2026 (1 hour 43 minutes)
The goal for today was to finish the CAD model for the ventilator. I began by finishing creating all of parts required for the actual mechniasm to work. 
Next, I spent time ensuring that all the parts work together properly by using Onshape assemblies. 
I used Revolute and Fasten mates to define the degrees of freedom of the mechanism and visualize the final motion of the system. 
Lastly, I added all fastener hardware. 
This required changing some parts to ensure that at most two bolt sizes would be needed when assembling. 
A design I incorporated extensively to make assembly easier was the use of nut inserts in the 3D-printed parts. 

<img height="250" alt="image" src="https://github.com/user-attachments/assets/7ca2bddd-4678-4d3f-9842-c2cdcff381b7" />

Final CAD Model

<img height="250" alt="image" src="https://github.com/user-attachments/assets/36d66f0c-de94-4fde-9d05-9925cffbb780" />
<img height="250" alt="image" src="https://github.com/user-attachments/assets/63d1b0d9-2411-409c-b961-8ffc13cfd052" />

Example of the use of nut inserts

## Session Three - May 9, 2026 (50 minutes)
During this session, my goal was to finish the wiring schematic for this project. I created the symbols and schematic using KiCAD. 
To create an accurate schematic, I designed four custom symbols in KiCAD. 
First, I made a symbol for the SPARK MAX motor controller that I intended to use for this project. This controller communicates with the ESP32 using PWM. 
Next, I made a symbol for the specific ESP32 Dev Module that I am using for this project. 
Next, I made a symbol for a simple 12V-to-5V buck converter. 
Finally, I made a symbol for the off-the-shelf LCD display that I am using for this project. 
For power, I am using a small power distribution board to supply 12V to the motor controller and a buck converter. 
The 5V output of the buck converter is then sent to a series of header pins on a protoboard to distribute power to the ESP32 and LCD displays. 


