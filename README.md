# stad
Repo that contains all or most code from the project STAD.


## Components in STAD:

1. UAV (PI and PixHawk6)
2. UGV (PX2)
3. Simulation

## Overview:

UAV and UGV code are running on ROS2 foxy distribution while the simulation is running with ros
humble distribution. The simulation is gazebo-classic with px4 since gazebo new version is not fully
developed and a some of functionalities does not work correctly with ros2.

In addition, on UGV you cannot run ros2 because it is running on Ubuntu 16.04. To make ros2 works
on UGV we run docker on it. We also installed docker on raspberry pi to make the installation easier
and if something goes wrong you can always create a new container. It is suggested to learn docker
basics before getting started it should not take more than a couple of hours to familiarize with the
basic commands.

