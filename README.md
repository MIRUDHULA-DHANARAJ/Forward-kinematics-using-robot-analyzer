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

# STEP 1:
Open the roboanalyzer software.

# STEP 2:
Select the robot and its degrees of freedom.

# STEP 3:
Change the values with the link lenght wherever necessary.

# STEP 4:
Simulate the model for forward kinematics.

# STEP 5:
Plot the graph between the link and the joints.

# STEP 6:
Update the DH parameters of the link configuration and end effector configuration.

## DH PARAMETERS

## 6 DOF:

![image](https://github.com/MIRUDHULA-DHANARAJ/Forward-kinematics-using-robot-analyzer/assets/94828147/adac6814-7a02-44be-a62c-394ad82967ad)

## 4 DOF:

![image](https://github.com/MIRUDHULA-DHANARAJ/Forward-kinematics-using-robot-analyzer/assets/94828147/5bb975a0-5f43-42d6-9803-475d5b02fd74)

## SIMULATION: 

## 6 DOF: 

![image](https://github.com/MIRUDHULA-DHANARAJ/Forward-kinematics-using-robot-analyzer/assets/94828147/297ccfb7-6f97-4de5-8dc8-6f607b8ab72d)

## 4 DOF:

![image](https://github.com/MIRUDHULA-DHANARAJ/Forward-kinematics-using-robot-analyzer/assets/94828147/7712d451-a424-401a-8d2a-c4db2424fafa)

## PLOT :
## 6 DOF:

![image](https://github.com/MIRUDHULA-DHANARAJ/Forward-kinematics-using-robot-analyzer/assets/94828147/ba9d2247-58d0-438f-b9f6-b4ddca3075b1)

## 4 DOF:

![image](https://github.com/MIRUDHULA-DHANARAJ/Forward-kinematics-using-robot-analyzer/assets/94828147/1b09ac05-0022-4d41-8b63-be0783018216)

## EE CONFIGURATION:

## 6 DOF: 

![image](https://github.com/MIRUDHULA-DHANARAJ/Forward-kinematics-using-robot-analyzer/assets/94828147/dbb502cb-94e2-4078-8126-d48e539f7491)

## 4 DOF: 

![image](https://github.com/MIRUDHULA-DHANARAJ/Forward-kinematics-using-robot-analyzer/assets/94828147/3d414257-a5ea-4db8-a99d-eef6770b8e84)

### RESULTS :  
The forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer has been analyzed and the graph for link cordinates and joint angles has been ploted.
