# Scenario1-ElectricTunnel-Dataset
UE4-based electric tunnel environments and data (RGBD, Lidar, IMU, etc.) collection scripts.

## Download dataset (rosbag file for each map)
  
  **Data description**
  
  Total 5 electric tunnel environments were built, each with distinctive tunnel shape, electric wire shape, wall and floor texture, and objects arrangement. Each environment is named as "MAP****_origin" and the changed version is named as "MAP****_change". Every environment is saved in the form of rosbag file, which contains all necessary information to explore the environment.
  
  **Contents in the rosbag file**
  
  - Current location

  **Difference between the original and changed environment**
  
  There are several differences between the original and changed environment. The basic structure of the tunnel including tunnel shape, electric wire, and wall and floor texture remains the same. But the situation in the tunnel such as objects arrangement or emergencies are mainly changed.

  - Change of the object location
    - Fall of fire extinguishers, lamps and warning signs
    - Translation or rotation of boxes and tanks
    - Generation of unkown objects such as wires, boxes, and even human
    
  - Emegencies
    - Fire, smoke and heat
  
  **Download Links**
  
<p float="left">
  <img src="fig/map0001_origin.png" width="360" />
  <img src="fig/map0001_change.png" width="360" /> 
</p>

  - [MAP0001_origin](https://drive.google.com/file/d/1_pSUbwMq98T1dgtgCeEd-ToUY7fZxlgm/view?usp=sharing, "MAP0001_origin") (1.15GB) 
  - [MAP0001_change](https://drive.google.com/file/d/1ZHmWIfhTQEjOIkAnlWg6cfE8iEFbHya_/view?usp=sharing, "MAP0001_change") (1.74GB)
  
  - [MAP0002_origin](https://drive.google.com/file/d/1y0Wv-iWMhhVl3zoDcdL9bVsMwpJhg8-A/view?usp=sharing, "MAP0002_origin") (1.18GB)
  - [MAP0002_change](https://drive.google.com/file/d/1rb7YVnYf7q-Y6M_5wWIRcSswI86kJ9SD/view?usp=sharing, "MAP0002_change") (0.57GB)

<p float="left">
  <img src="fig/map0003_origin.png" width="360" />
  <img src="fig/map0003_change.png" width="360" /> 
</p>
  
  - [MAP0003_origin](https://drive.google.com/file/d/1fh94qG18Mayj5fE4xJ-gy9nhYKexIWoy/view?usp=sharing, "MAP0003_origin") (1.45GB)
  - [MAP0003_change](https://drive.google.com/file/d/1HstErqNMKtuD-67nAb3LWKUVB76LaOJ2/view?usp=sharing, "MAP0003_change") (1.13GB)
  
  - [MAP0004_origin](https://drive.google.com/file/d/13MeAWOc5WOYVn9bAFwmjGGabcR8XtDoM/view?usp=sharing, "MAP0004_origin") (1.53GB)
  - [MAP0004_change](https://drive.google.com/file/d/1KA8X0KLJCEWDFL96Yf2U5dv6-ItSGqfU/view?usp=sharing, "MAP0004_change") (1.23GB)
  
  - [MAP0005_origin](https://drive.google.com/file/d/16kT7HrnBB4p73d2xkJU1tA271j-WaMye/view?usp=sharing, "MAP0005_origin") (1.09GB)
  - [MAP0005_change](https://drive.google.com/file/d/1-9mGh5VEs36ioS13555kJw8bbg6XFNV5/view?usp=sharing, "MAP0005_change") (1.34GB)
  
## Play with data

  -T.B.U. 

## Create your own dataset

  **1.** Environment setup
    - Follow instruction [here](https://github.com/SAMMiCA/Scenario1-3D-Change-Detection/edit/main/README.md)

  **2.** Build electric tunnel with UE4
    - Purchase 
    - Tutorial
    
  **3.** Run AirSim on the project
  
  **4.** Open new terminal
