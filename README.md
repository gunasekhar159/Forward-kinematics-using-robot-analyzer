# Forward-kinematics-using-robo-analyzer

## AIM: 
To analyze the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles
### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
Forward Kinematics

A manipulator is composed of serial links which are affixed to each other revolute or prismatic joints from the base frame through the endeffector. 
Calculating the position and orientation of the endeffector in terms of the joint variables is called as forward kinematics. 
In order to have forward kinematics for a robot mechanism in a systematic manner, one should use a suitable kinematics model. 
Denavit-Hartenberg method that uses four parameters is the most common method for describing the robot kinematics. 
These parameters ai1, α −,1idi and θ the link length, link twist, link offset and joint angle, respectively. 
A coordinate frame is attached to each joint to determine DH parameters. Zi axis of the coordinate frame is pointing along the rotary or sliding direction general manipulator.

Denavit Hartenberg Parameters
With DH Parameters, solving for the Forward Kinematics is easy.  only need to take four parameters for each joint 
i: θifor the joint angle, 
αi for the link twist, 
difor the link offset, and 
ai for the link length. Once I’ve obtained them, I can just plug them in to this transformation matrix:


![image](https://user-images.githubusercontent.com/36288975/170172719-ed7befc9-2894-4344-bfd5-be831bb05308.png)

 ![image](https://user-images.githubusercontent.com/36288975/170172766-b8aeb788-7fd7-4de7-b340-f04656707ebd.png)

 

### PROCEDURE:
## step1:
open the robot analyzer software.
## step2:
select the robot and its degrees of freedom.
## step3:
change the values with the link length whenever necessary.
## step4:
simulate the model for forward kinematics.
## step5:
pick the graph between the link and the joints.
## step6:
update the Dh parameters of the link configuration and endeffector configuration.




### SIMULATION 
![output](https://github.com/gunasekhar159/Forward-kinematics-using-robot-analyzer/blob/main/2.png?raw=true)

![output](https://github.com/gunasekhar159/Forward-kinematics-using-robot-analyzer/blob/main/1.png?raw=true)
 
 
 
  ### PLOT 
  ![output](https://github.com/gunasekhar159/Forward-kinematics-using-robot-analyzer/blob/main/3.png?raw=true)
  
  ![output](https://github.com/gunasekhar159/Forward-kinematics-using-robot-analyzer/blob/main/4.png?raw=true)

 
 
### RESULTS :  
Thus, the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted..
