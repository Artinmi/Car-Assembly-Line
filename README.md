#  Car Assembly Line Simulation in RoboDK
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
7. [Credits](#credits)


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

1. 🦾 KUKA-KR-50-R2500
       - Function: Responsible for handling and installing the car doors.
       - Payload: 50 kg
   

      


## Programming



## Challenges


## Usage


## Credits
The goal of this project was to design a functional robotic leg that could be optimized using the Particle

