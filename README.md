## JAVA Simulation Project
## Team members:

1. Mohaned Khaled Hassan Hassan 2001372
2. Mohammed Magdy Mahrous 2000927
3. Mostafa Hessin Ahmed Qenawy 2000931
4. Salma Yasser Abdelmageed Meckawy Hemdan 20P7211
5. Sara Yasser Abdelmageed Meckawy Hemdan 20P8099
##

## Description
A real-time software system that opens Simulink MDL files in a Java based GUI

The tool is made up of two main things: 
 1. a file reader that understands MDL files
 2. a user interface built with Java
 
 The file reader reads the MDL file and gets all the important information like diagrams and connections. 
 <br>
 The user interface shows the model in an easy-to-understand way and lets us interact with it.
 
 
 ## Features of the program include:
 First: run the program:
 <br>
  -The graphical user interface (GUI) of the program will appear on the screen
 ##
 Second: file managment:
 <br>
 Loading Simulink MDL Files: 
 <br>
  -The program allows us to import Simulink MDL files, which contain the model information.
 ##
 Third: file Parsing:
 <br>
  -Once the file is selected, the program begins reading its contents.
 <br>
  -It searches for a specific marker, "MWOPC_PART_BEGIN /simulink/systems/system_root.xml", which indicates the start of the block and line details.
 ##
 Fourth: Block, Line and Branches Details Extraction:
 <br>
  -From the marker onwards, the program extracts information about the blocks present in the model.
  <br>
  -It captures details such as the position of the blocks, their source code, destination, and the number of ports they have.
  <br>
  -Similarly, the program also retrieves information about the lines connecting the blocks, including their source and destination connections.
  <br>
##
 Fifth: Structure Display and model Visualization: 
 <br>
 -The program will display the contents of the MDL file in a hierarchical structure. 
 <br>
 -The GUI provides a visual representation of the model components such as block diagrams, parameters, and connections. 
 ##
 Sixth: Real-time Visualization: 
 <br>
 -When we make changes to the model interactively, the program will immediately update the visualization to reflect those changes.
 

## Output
![image](https://github.com/MohanadKhh/JAVA_Simulation_Project/assets/132143243/6db9145b-f42f-46e4-b021-4f6d0e2147b2)
<br>
##
![image](https://github.com/MohanadKhh/JAVA_Simulation_Project/assets/132143243/e9dfa077-bc16-4f89-8e0e-f72a78209acc)
<br>
##
![image](https://github.com/MohanadKhh/JAVA_Simulation_Project/assets/132143243/ea984b74-b1ac-4e75-a4c7-28c9ba5703c2)
<br>
##
## Project run video

https://github.com/MohanadKhh/JAVA_Simulation_Project/assets/132143243/00f2a067-6518-4554-9233-512a152013af

