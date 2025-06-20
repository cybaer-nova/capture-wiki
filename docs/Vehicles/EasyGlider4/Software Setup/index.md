## Software Stack

The software stack, as detailed above, was used to implement and validate the simulation and autonomous flight. It includes:

- **PX4 Autopilot:** Open-source flight control software for Unmanned Vehicles 
- **Gazebo:** 3D simulation environment for realistic physics modeling 
- **MAVSDK:** API for communicating with PX4 and executing autonomous commands 
- **QGroundControl (QGC):** Used to configure flight parameters and visualize the flight  

The PX4 firmware was configured to support fixed-wing flight dynamics.  
Gazebo was customized to include accurate aerodynamic properties.  
MAVSDK enabled communication via MAVLink messages between the Raspberry Pi Zero 2W and the PX4 flight controller (Holybro),  
allowing waypoint-based autonomous navigation. QGC was used for real-time monitoring and PX4 parameter modifications.
