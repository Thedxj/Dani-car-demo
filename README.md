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
## Contributing

We welcome contributions from the community to improve this project! Here's how you can get involved:

**1. Fork the Repository:**

Head over to [https://github.com/Thedxj/Dani-car-demo.git](https://github.com/Thedxj/Dani-car-demo.git) and fork the repository. This creates your own copy of the code that you can modify.

**2. Make Changes:**

Clone your forked repository to your local machine, make your desired changes, and commit them locally. 

**3. Create a Pull Request:**

Push your changes to your forked repository and create a pull request to the main branch of the original repository. This sends a notification to the project maintainers about your proposed contribution.

**4. We Review and Discuss:**

Project maintainers will review your pull request and provide feedback. This could involve suggesting improvements, clarifying points, or simply merging your changes if they're a good fit.

**What We Appreciate:**

We're open to contributions that can enhance the simulation in various ways:

- Adding additional features to the environment (e.g., obstacles, sensors)
- Improving teleoperation functionality (e.g., smoother control, additional control options)
- Enhancing documentation (e.g., clearer instructions, tutorials)
- Fixing bugs or technical issues

**Feel free to reach out!**

If you have any questions or need guidance during the contribution process, don't hesitate to open an issue or contact the project maintainers. We appreciate your interest in contributing!
