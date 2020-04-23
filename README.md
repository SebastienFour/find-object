# [find_object_2D](https://github.com/SamuelHuet/simple_navigation_goals)

_[![ROS Melodic](https://img.shields.io/badge/ROS-Melodic-red)](http://wiki.ros.org/melodic/Installation/Ubuntu)_ _[![TurtleBot3](https://img.shields.io/badge/TurtleBot-3-brightgreen)](http://emanual.robotis.com/docs/en/platform/turtlebot3/pc_setup/)_ ![OpenCV](https://img.shields.io/badge/OpenCV-2-yellow) ![LICENSE](https://img.shields.io/badge/LICENSE-Apache%202.0-informational)

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/bb/Ros_logo.svg/800px-Ros_logo.svg.png" width="110"> ![MelodicTurtle][melodic-turtle]

>Project prototype using ROS with openCV for tracking applications.

- [find_object_2D](#findobject2d)
  - [Installation](#installation)
  - [How To Run](#how-to-run)
  - [Meta](#meta)
  - [Contributing](#contributing)

## Installation

Simply clone this repository on your computer and compile the project using catkin_make:
```
$ cd ~/catkin_ws/src
$ git clone https://github.com/SebastienFour/find-object.git
$ cd ~/catkin_ws
$ catkin_make
```

## How To Run

```
$ cd ~/catkin_ws/src/find_object
$ roscore &
$ rosrun find_object_2d find_object_2d image:=/camera/rgb/image_raw
```

## Meta

Distributed under the Apache 2.0 license. See ``LICENSE`` for more information.

## Contributing

1. Fork it (<https://github.com/introlab/find-object/fork>)
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

<!-- Markdown link & img dfn's -->
[melodic-turtle]: https://raw.githubusercontent.com/ros/ros_tutorials/melodic-devel/turtlesim/images/melodic.png
