# CARLA Autonomous Vehicle Motion Planning

## Requirements

You will need to install the CARLA simulator first. Inside the python client file in the CARLA package, install the project files. Make sure to follow the PDF document to install the right version of CARLA. You will also need the to install the depenedncies from the requirments file.

## Why I Built This Project

The primary motivation behind this project was my passion for **robotics, control systems, and mechatronics**. Automation is a key area of interest for me, and I believe that self-driving cars represent the future of transportation. This project allowed me to explore the fundamentals of autonomous vehicle navigation while applying concepts that are crucial for my career growth in robotics and automation. Additionally, as part of a Coursera course, this project provided an excellent opportunity to enhance my technical skills and contribute to my understanding of real-world applications in autonomous systems.

### Objectives:
- Develop a Python-based autonomous driving system using the CARLA simulator.
- Implement key functionalities such as obstacle avoidance, vehicle following, traffic sign recognition, and navigation.
- Gain hands-on experience with motion planning and control algorithms.

## How It Works

This project utilizes the CARLA simulator to create an autonomous driving system capable of navigating a virtual environment. The following features were implemented:

1. **Road Navigation**: The vehicle autonomously follows a predefined path using motion planning algorithms.
2. **Obstacle Avoidance**: The system detects parked vehicles and dynamically adjusts its trajectory to avoid collisions.
3. **Vehicle Following**: The car maintains a safe distance while following another vehicle on the road.
4. **Traffic Sign Recognition**: The system stops at stop signs and adheres to other traffic rules.
5. **Turning Maneuvers**: Smooth turning at intersections is achieved using path planning techniques.
6. **Traffic Light Compliance**: The car halts at red lights and resumes movement when the light turns green.

The entire process is governed by Python scripts that interact with CARLA's API to control the vehicle's sensors, actuators, and decision-making logic.

## Results

The project successfully demonstrated the following outcomes:
- Seamless navigation through a simulated environment while adhering to traffic rules.
- Effective obstacle avoidance and vehicle following capabilities.
- Accurate recognition of stop signs and traffic lights.
- Smooth execution of turns at intersections.

This simulation highlights the potential of autonomous driving systems in controlled environments and serves as a foundation for further exploration in self-driving car technologies.

## Credits

This project was developed as part of a Coursera course on autonomous systems. I would like to express my gratitude to:
- **Coursera instructors** for providing valuable insights into autonomous driving principles.
- The **CARLA simulator community** for creating an open-source platform for testing autonomous vehicle algorithms.
- My academic background in robotics, control systems, and mechatronics, which equipped me with the necessary skills to complete this project.
