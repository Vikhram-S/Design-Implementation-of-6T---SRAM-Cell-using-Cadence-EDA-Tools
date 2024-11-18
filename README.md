# Ex No: 04 Design-Implementation-of-6T--SRAM-Cell-using-Cadence-EDA-Tools
     

## Aim:

To design and implement a 6T SRAM (Static Random-Access Memory) cell using Cadence EDA tools, simulate its functionality, and analyze key performance parameters such as read/write operations, power consumption, and stability to understand its behavior in memory design.

## Tools Required:

•	Personal Computer

•	Cadence Virtuoso Software


## Circuit Diagram:

![IMG-20241115-WA0004](https://github.com/user-attachments/assets/86635ce5-4ffc-484d-aa49-7a2d5ad428bf)


## SCHEMATIC SIMULATION:

PROCEDURE FOR CREATING THE SCHEMATIC SIMULATION
Commands to get into Cadence
1.	Right Click and open the terminal window
2.	Type the following commands as follows and press enter.
•	csh
•	source /cadence/install/cshrc
•	virtuoso 
Procedure for Schematic simulation using Cadence

1.	Now two windows must open i)virtuoso/command interpreter window ii)”Whats New…”
2.	Close the 2nd window
3.	Use 1st window i.e virtuoso window(CIW) for further processing.
i.	Create a New Library
ii.	Create Schematic Cell view.
iii.	Create the Symbol for schematic Cell view.
iv.	Create the test Cell view.
v.	Analog simulation by spectre



i)	Procedure for Creating New Library.

•	File –New – Library

•	Name : Give name for ur library Ex: VLSILAB_EXP_1

•	Enable Attach to an existing technology library, Click OK

•	Attach the library to the technology library gpdk045.Click OK

ii)	Create Schematic Cell view.

•	Go to 1st window i.e virtuoso(CIW)

•	File-New-Cell view

•	Setup the new file form
	  Library: Select the one you a created.
	  Cell : Give the experiment name Ex: Inverter View_Schematic
	  Type: Schematic press OK
•	Add the required components from the libraries and make the connections.

• Go to instance fixed menu or use shortcut key “I” from keypad to go instances

•	Click on browse. This opens the library browser

•	Now select the appropriate library for components like 
• Gpdk45 ------------------------nmos1v,  pmos1v

• Create Input and Output pins

•	Make the connections by using fixed narrow wire key

•	Click Check and Save button
![Screenshot 2024-11-11 103039](https://github.com/user-attachments/assets/697dffe8-9c46-4706-9f3a-075977e4b361)



 
iii)	Creating the Symbol for schematic Cell view

•	In the schematic window, execute 

•	Create – Cell view – From Cell view

•	The cell view from cell view window appears

•	Check Lib Name, Cell Name, From View name must be schematic Press ok

•	Now Symbol generation form appears. Click Ok If No changes required

•	A new window with with default symbol is created.

•	Edit the symbol if you want to give actual symbol shape else continue.

•	Execute Create-Cell view-from cell view

•	Library Name and Cell Name must be same which you have used for schematic. Press OK

•	Check for the position of pin side.Prss OK

•	Edit for the shape by Create-Shape-Choose required options to edit.


## Analog simulation by SPECTRE:
•	In test cell view window

•	Launch – ADE L(Analog Design Environment)

•	Execute Setup—Simulation/directory/Host A new window opens

•	Set the simulation window to spectre and click ok

•	Execute Analysis – Choose. A window opens.

•	Select the type and set the specifications and press OK

•	Execute Output s—to be plotted – Select on Schematic

•	Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse

•	Execute Simulation -- Net list and Run
![Screenshot 2024-11-11 102829](https://github.com/user-attachments/assets/6642f29e-b6ea-48d6-8dda-11a5f6d8a75b)



## For Transient Analysis Settings and Output

![Screenshot 2024-11-11 102857](https://github.com/user-attachments/assets/3e5535cf-10f5-4265-8146-6452b2adce62)
![Screenshot 2024-11-11 103529](https://github.com/user-attachments/assets/d87637d4-5bc7-44bf-99a4-a837da93ef42)



## Result:

The design and implementation of the 6T SRAM cell using Cadence EDA tools were successfully achieved. Simulation results validated the correct functionality and performance of the SRAM cell, including stable read/write operations.










