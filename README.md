# 🚗⚙️🤖 Car Assembly Line Simulation in RoboDK
This repository contains a simulation of an **automated Car Assembly Line** built using **RoboDK**, where **robotic arms** perform **precise and efficient** installation of car doors and the front windshield. The project demonstrates the potential of robotic automation in automotive manufacturing, leveraging **inverse kinematics** for **high-precision assembly**.

<p align="center">
  <img src="fhttps://github.com/Artinmi/Robot-Leg-4bar-PSO/blob/master/docs/leg.gif" width="45%" alt="Leg"/>
</p>

The simulation includes:

✅ Conveyor system for car movement

✅ Two KUKA robotic arms for automated door and windshield installation
- KUKA-KR-50-R2500 – responsible for handling and assembling the car doors.
- KUKA-KR-360-2 – tasked with positioning and installing the front windshield.
  
✅ Inverse kinematics-based programming for precise positioning

✅ Multi-stage assembly process to simulate a real-world production line


## Table of Contents
1. [Introduction](#introduction)
2. [Design Process of Assembly line](#Design-Process-of-Assembly-line)
3. [Robot Arms](#Robot-Arms)
4. [Programming](#Programming)
5. [Challenges](#Challenges)
6. [Usage](#usage)
7. [Conclusion](#Conclusion)
8. [Credits](#credits)


## Introduction
Robotic automation has revolutionized modern **automotive production, ensuring high precision, efficiency, and scalability**. This project simulates a car assembly line using **RoboDK**, where two **KUKA robotic arms** perform **door and windshield** installation in a structured two-stage process.

The main objective of this project is to demonstrate the automation potential of robotic arms in a car manufacturing setting. Using conveyors, robotic arms, and precise inverse kinematics programming, the project successfully replicates a real-world car assembly line.

**Key Features**

- Fully simulated assembly line with conveyors, robots, and car components

- Automated door and windshield installation process

- High-precision motion control using inverse kinematics

- Two industrial robotic arms working in coordination

- Scalable and adaptable simulation for real-world manufacturing applications


## Design Process of Assembly line
The car assembly line consists of a multi-stage workflow, where robotic arms interact with the moving car. The design process involves:

1. Setting up the Conveyor System:
   - The conveyor moves the car to predefined positions, ensuring that robots can operate efficiently.
2. Positioning the Robotic Arms:
   - Two KUKA robotic arms are placed on either side of the conveyor to handle the doors and windshield installation.
3. Defining Assembly Stages:
   - Stage 1: Door Installation
      - The left robotic arm installs the left door.
      - The right robotic arm installs the right door.
   - Stage 2: Windshield Installation
      - The right robotic arm applies glue to the car frame.
      - The right robotic arm picks up the windshield and places it precisely.
  
4. Programming the Motion Sequences:
     - Target points are set for each movement.
     - Robots follow pre-programmed inverse kinematics paths to reach targets with high accuracy.

## Robot Arms
This project utilizes two powerful KUKA robotic arms, chosen for their precision, durability, and payload capacity:


1. 🦾 KUKA-KR-50-R2500:
   - Function: Responsible for handling and installing the car doors.
   - Payload: 50 kg
   - Reach: 2500 mm
   - Application: Used for picking up doors and placing them onto the car frame.

2. 🦾 KUKA-KR-360-2:
   - Function: Responsible for windshield installation.
   - Payload: 360 kg
   - Reach: 2826 mm
   - Application: Used for applying glue and placing the windshield with high precision.



Both robotic arms are programmed to work simultaneously and efficiently, ensuring smooth automation.
      


## Programming
The robot arms are programmed using inverse kinematics, which enables precise movement to predefined target points. The programming follows a structured sequence:

1. 🟢 Step 1: Define Targets:
    - Multiple target points are set for door and windshield installation.
    - Each robot is assigned specific waypoints to ensure smooth movement.
  
2. 🟢 Step 2: Inverse Kinematics Implementation
    - Robots use inverse kinematics to calculate joint movements, ensuring high accuracy and repeatability.
    - RoboDK provides offline programming, allowing efficient simulation before real-world implementation.
  
3. 🟢 Step 3: Execution of Assembly Tasks
    - Stage 1: Installing the Left and Right Doors
      - Left Robot: Picks up the left door and aligns it with the car frame.
      - Right Robot: Picks up the right door and installs it in place.
      - Both robots synchronize their movements for simultaneous door installation.

    - Stage 2: Installing the Front Windshield
      - Right Robot: Applies glue to the windshield area.
      - Right Robot: Picks up the windshield and carefully places it with high precision.

**The robots operate in perfect coordination, replicating an industrial assembly line.**



## Challenges
🔴 Precision in Door and Windshield Placement
  - The robots needed high accuracy to ensure that doors and windshields fit correctly.
  - This was resolved using precise inverse kinematics calculations and well-defined target points.


🔴 Synchronization Between Robots
  -The two robots had to work in perfect coordination to avoid collisions.
  -This was managed by carefully timing their movements and optimizing target placement.


🔴 Conveyor Speed and Timing
  - Ensuring that the conveyor moves at the correct speed was critical.
  - The conveyor timing was calibrated to allow efficient robotic interaction.




## Usage
This project is a great example of robotic automation in car manufacturing. The simulation can be used for:

✅ Educational Purposes – Learning about robotics, automation, and programming.

✅ Manufacturing Prototyping – Testing assembly line automation before real-world implementation.

✅ Research in Robotics – Optimizing robotic movements and synchronization techniques.

🛠 Requirements
  - RoboDK software
  - Basic knowledge of robotic programming & inverse kinematics
  - A system capable of running robotic simulations

▶️ Running the Simulation
  1. Open RoboDK and load the project file.
  2. Run the robotic arms program to install doors and the windshield.
  3. Observe the precise execution of the assembly process.


## 📌 Conclusion
This simulation showcases how robotic automation can improve efficiency in automotive manufacturing. By using KUKA robotic arms, precise inverse kinematics programming, and a structured assembly process, this project successfully replicates a real-world automated car production line.

🚀 Future Improvements:

  - Integration of AI-based error detection for quality control
  -Optimization of robotic arm speed and trajectory planning
  -Expansion to include additional assembly tasks

## Credits
This project was developed by:
- **Artin Mokhtariha** & **Taha Faghani** – Design, Optimization, Programming(Python and Arduino) ,and setup installation.
- **Negar Asadi** – 3D Printing and Assembly


### Contributions
Contributions are always welcome! If you'd like to improve the project or add new features:
1. Fork this repository.
2. Create a new branch for your feature or fix.
3. Submit a pull request for review.

### Contact
If you have any questions or suggestions, feel free to reach out:

- Artin Mokhtariha - [artin1382mokhtariha@gmail.com](mailto:artin1382mokhtariha@gmail.com)
- GitHub: [Artinmi](https://github.com/Artinmi)
- Linkedin Post: [Clich here]()



## Credits
The goal of this project was to design a functional robotic leg that could be optimized using the Particle

