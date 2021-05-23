# APC(Autonomous Patrol Car)

## Introduction

APC(Autonomous Patrol Car) is a car which patrols home using ROS + Raspberry Pi +  This project is started from an idea that "it would be great if i have a car patrols around home autonomously. like a dog."

## Features

- Patrol
- 4-Axis(Pan, Tilt, X-Y Move) Serveliance (it will support ONVIF so that standalone-NVR recognizes it as IPCamera. then, videos will be stored HDD.)
- Measures Outside data and send it to Cranberry(home IoT System, it will be helpful if you check out my another repository.)

## Development Plan

### Phase1 - Manual Control

1. Add Solar Cell as power Source
2. Add Webcam + Raspberry Pi and stream to hikvision DVR
3. Enclosure Design
4. add NodeMCU in order to control Basement 
5. create server

### Phase2 - Autonomous Control

1. Buy & install ydlidar 
2. install ROS
3. coding.

