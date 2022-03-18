# IMU-based pointing for package selection on industrial conveyor belts

*submitted at CASE22*

*Gabriele Abbate, Alessandro Giusti, Antonio Paolillo, Luca Maria Gambardella, Andrea Emilio Rizzoli and Jérôme Guzzi*

Dalle Molle Institute for Artificial Intelligence, USI-SUPSI, Lugano (Switzerland)

This work is supported by the European Commission through the Horizon 2020 project 1-SWARM, grant ID 871743.
### Abstract

We introduce an intuitive pointing-based interface to select objects moving on a system of conveyor belts. 
The interface has minimal sensing requirements, as the operator only needs to wear an Inertial Measurement Unit on the wrist (e.g., a smartwatch).
LED strips provide the required visual feedback to precisely point to the objects and select them.
We experimentally compare the proposed approach with a baseline mouse-based graphical user interface in which the user can click on packages with a mouse.
Quantitative results show that our interface compares favorably to the baseline, especially in difficult scenarios involving many packages moving fast.

### Repository Structure
This repository is organized as follows:
- `submission`: contains the video submission, supplementary video materials, experimental datasets and code to analyze them.

### Video Submission (click to open on youtube)

[![IMU-based  pointing  for  package  selection  on  industrial  conveyor  belts](https://github.com/idsia-robotics/pointing-belts/blob/master/submission/thumbnails/video_sub.gif)](https://youtu.be/hB33cX6pvmg)

### Supplementary Video
#### Virtual Reality World and Real World Overlapping (click to open on youtube)
[![Virtual Reality World and Real World Overlapping](https://github.com/idsia-robotics/pointing-belts/blob/master/submission/thumbnails/overlap.gif)](https://youtu.be/an0PUn2B63Y)

The video shows the user performing the relative localization and the pointing phase, highlighting the overlap between the VR and the real world scenarios.

#### Pointing Interface VR Demo with Conveyor Belt Demonstrator (click to open on youtube)
[![Pointing Interface VR Demo](https://github.com/idsia-robotics/pointing-belts/blob/master/submission/thumbnails/demo.gif)](https://youtu.be/3J1HDkwa8qU)

The video shows a couple of runs where the user is interacting with the conveyor belt system. Once the user notices a red (anomalous) package, he triggers the relative localization and then points at that package.
Selected packages are diverted towards the first unloading bay, unselected packages towards the third one.
