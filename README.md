# Four-Wheeled Mobile Robot with Differential Drive Plugin in an H Model Environment
This is a ROS package that simulates a four-wheeled mobile robot with a differential drive plugin in an H Model environment. The package allows for maneuvering the robot within the simulated environment using the teleop twist keyboard.

### Prerequisites
This package requires the following software to be installed on your system:

ROS (Robot Operating System) - this package was tested on ROS Melodic and Noetic
Gazebo simulator
teleop_twist_keyboard package

### Installation

1. Clone this repository to your local machine:
```bash:
git clone https://github.com/Thedxj/Dani-car-demo.git
```

2. Navigate to the four-wheeled-mobile-robot directory:
```bash
cd Dani-car-demo
```

3. Build the package using catkin_make:
```bash:
catkin_make
```

4. Source the ROS environment:
```shell
$ source devel/setup.bash
```

5. Launch the simulation:
```ruby
$ roslaunch mobile_robot_simulator mobile_robot.launch
```
This will launch Gazebo with the mobile robot in an H model environment.

6, Launch the teleop_twist_keyboard node:
```ruby
$ rosrun teleop_twist_keyboard teleop_twist_keyboard.py
```
This will launch the keyboard teleoperation node that allows you to control the movement of the robot.

### Contributing
If you would like to contribute to this project, please fork the repository and submit pull requests. We welcome any contributions that can improve the simulation and its functionalities..
