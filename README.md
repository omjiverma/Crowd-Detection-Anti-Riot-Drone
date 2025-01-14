# Crowd Detection Anti-Riot Drone

An advanced drone system designed to aid armed forces in crowd monitoring and riot control by deploying tear gas canisters and providing real-time surveillance.

## Table of Contents

- About the Project

- Features

- Project Objectives

- Components Used

- Drone Methodology

- Neural Network Integration

- Results

- How to Operate

- Future Scope

- Acknowledgments

### About the Project

The Crowd Detection Anti-Riot Drone is a UAV (Unmanned Aerial Vehicle) designed to aid in riot control. It enables armed forces to monitor crowds from a safe distance and deploy tear gas canisters using a servo mechanism. This solution reduces risks to personnel and improves crowd control efficiency.

### Features

- Real-time crowd detection using deep neural networks.

- Live video streaming to monitor the ground situation.

- Deployment of tear gas canisters using a servo mechanism.

- Remote control operation via an RC transmitter and receiver.

- Stable quadcopter design with robust flight capabilities.

### Project Objectives

- Detect crowds at an initial stage using video surveillance.

- Perform area monitoring and surveillance.

- Launch tear gas canisters without direct engagement.

- Provide real-time visual feedback to operators.

### Components Used

- F450 Quadcopter Frame: Durable and lightweight.

- Brushless Motors: A2212 1400kV for quadcopter propulsion.

- Electronic Speed Controllers (ESC): 30A BLDC for motor control.

- Propellers: 10x4.5-inch propellers for smooth and efficient flight.

- LiPo Battery: High-capacity rechargeable battery.

- Flight Controller: Custom-built using the MultiWii open-source platform.

- Transmitter and Receiver: NRF24L01 module for remote control.

- Camera Module: For real-time video capture and streaming.

### Drone Methodology

* 1. Vertical Motion

Adjust rotor speed to ascend, descend, or hover.

* 2. Turning and Rotating

Differential rotor speeds are used to control yaw.

* 3. Forward and Sideways Motion

Modulate rotor speed to tilt and move in the desired direction.

### Neural Network Integration

- The drone uses a lightweight deep neural network to:

- Detect and differentiate between crowded and uncrowded areas.

- Analyze live video feeds for crowd behavior.

- The YOLOv3 (You Only Look Once) model was used for object detection.

Results

- Successfully assembled and tested the quadcopter.

- Stable flight achieved 

- Real-time crowd detection

- Effective deployment of tear gas canisters in controlled tests.

### How to Operate

* Drone Setup:

- Place the drone on a flat surface.

- Connect the battery to the XT6 connectors.

- Power on the transmitter.

- Arm the drone by setting the throttle to 0 and yaw to maximum.

- Disarm the drone by setting both yaw and throttle to minimum.

### Camera and Crowd Detection:

- Set up a Wi-Fi hotspot named dronecam with the password dronecame.

-Connect the drone camera and your laptop to the hotspot.

- Run the Python script for crowd detection.

### Future Scope

- Integrate GPS for autonomous navigation.

- Improve battery efficiency for extended flight times.

- Add advanced sensors like thermal cameras for enhanced surveillance.

- Develop a mobile app for better user control and data visualization.

### Acknowledgments

We extend our gratitude to our project guides, Er. Atul Agnihotri and Dr. Vishal Awasthi, for their invaluable guidance. Special thanks to C.S.J.M. University, Kanpur, for providing the platform and resources to bring this project to life.

### Contributors:

* Omji Verma
* Md. Azhar Khan
* Praveen Tiwari
* Pankaj Kumar Singh
