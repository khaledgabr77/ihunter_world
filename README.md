# iHunter Project: ROS2 Gazebo Garden World Environment

This project contains a custom Gazebo Garden world for the iHunter project, designed for use with ROS2. The environment includes several key components necessary for simulation and testing.

## World Components

The iHunter world includes the following models:

1. **Ground Station**: Central control hub for managing operations.
2. **Pickup**: Holds the interceptor unit for deployment.
3. **Military Base**: Complete with the Saudi Arabian flag, representing a defense location.
4. **Radar Pole**: Essential for hold Radar.
5. **Ground Radar**: A system for tracking incoming objects or threats.
6. **Radio Tower**: Facilitates communication across the environment.
7. **Sand Model**: Adds realistic desert terrain to the world.
8. **Red Box**: Holds the target unit for deployment.

![alt text](<Screenshot from 2024-09-19 11-54-52.png>)
![alt text](<Screenshot from 2024-09-19 11-55-17.png>)
![alt text](<Screenshot from 2024-09-19 11-57-43.png>)

## Installation

To use this environment in Gazebo Garden, follow these steps:

1. Copy all the models into your Gazebo model path.

2. Launch the simulation by running the following command:

    ```bash
    gz sim default.sdf
    ```

## Requirements

- ROS2 Humble
- Gazebo Garden
- Gazebo model path properly configured
