# AI Engineer and Roboticist

#### Technical Skills: Python, C++, Tensorflow, Keras, Px4-autopilot, Robot Operating System, OpenCV, Flask

## Education
- B.E, Mechanical | SSN college of Engineering (_May 2023_)								       		


## Work Experience
**AI and Navigation Engineer @ Skytex Unmanned Aerial Vehicles Pvt Ltd (_July 2023 - Present_)**
### CACTUS
- A VTOL Fixed Wing decentralized swarm system that exhibits all swarm capablities namingly schooling, flocking, foraging, payload dropping, object detection and collision avoidance. 
- Designed novel vector field guidance algorithm for smooth navigation of the swarm system. 
- Developed network stack for efficient communication among the uavs. 
- Wrote mavlink commands, which will be sent to the PX4 autopilot from a jetson xavier-nx onboard computer using ROS2 and UXRCE agent. 
- The swarm is capable of flying at an altitude of 3km and performs on air collision as well as obstacle avoidance. 
- A custom web-gcs to plan and execute own missions.

### BUMBLEBEE
- Palm sized quadrotor equipped with Jetson Orin-nx that navigates through gps-denied forest environment and executes a lissajous search pattern. 
- Developed slam using RTABMAP which generates the cloud points of the local obstacles.
- Obstacle points are fed to A-star path-planning algorithm to generate next set of waypoints. 
- Designed a 3d vector field algorithm to execute the trajectory and in order to ensure a
smooth transition from current waypoint to the next.
- Performs target verification using a Siamese neural networks.


## Projects
### Chess Playing Robot Arm

Built a 5-dof non-holonomic articulated manipulator that plays chess one-on-one with human. Trained a simple convolutional neural network that identifies the chess-coin type in every location of the board and converts it to Forsyth–Edwards Notation. Image subtraction algorithm the finds the coin location to perform pick-and-place operation. The computer vision stack runs inside a raspberry-pi 3b+ whereas the inverse kinematics as well as the pick-and-place stack runs inside arduino uno. The communication happens via rosserial.

![Arm](/assets/img/arm.jpg)

### Face Recognition

Developed and attendance management system using Siamese neural networks architecture. The network was trained on both crossentropy and triplet loss. The dataset consists of 450 pictures of 15 employees working in a small scaled company. The whole architecture is embedded into RaspberryPi-3b+ and the camera used was logitech c270.

### Autonomous pick and place drone

Designed and Built a quadrotor equipped with a 3d printed solenoid gripper for pick and place action. Camera and a TFmini lidar attached to the bottom of the drones senses (object detection) the object of interest on the ground at the same time maintaining the current altitude (2m). Uses Pixhawk flight controller with RaspberryPi-3b+ as a companion computer to send and receive MAVLINK commands. The entire stack was built using Drone-Kit and ROS for easy and efficient communication between all hardware components as well the scripts.

![Autonomous drone](/assets/img/autonomous_drone.jpg)

### Jaffa-Sparrow
Trained a tiny interactive language model trained in native tamil. The model was trained on multilingual c4 (mc4), news articles, tiny books, wikipedia datasets. Training was done on 2 x 4060ti gpu (Single host multi device strategy) with data parallelism. The model was later fine-tuned on tamil converstions datasets to be able to carry out multi-turn conversations. 



## Publications
1. Santosh S, Bavin S, Srivatsan TS. Comparing surface characteristics of Cu-Al-Fe alloys using thermal-based machining processes., Surface Engineering. 2024;40(5):558-567.
doi:10.1177/02670844241276371
2. Santosh S, Bavin S. Experimental Studies on Wire Electric Discharge Machining of
Copper-Aluminium-Iron Ternary Shape Memory Alloy, (under review in Physica Scripta), IOP
publishing company

