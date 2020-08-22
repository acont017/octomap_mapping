octomap_mapping [![Build Status](https://travis-ci.org/OctoMap/octomap_mapping.svg?branch=kinetic-devel)](https://travis-ci.org/OctoMap/octomap_mapping)
===============

ROS stack for mapping with OctoMap, contains the `octomap_server` package.

The main branch for Kinetic, Melodic, and Noetic is `kinetic-devel`.

Indigo: [![Build Status](https://travis-ci.org/OctoMap/octomap_mapping.svg?branch=indigo-devel)](https://travis-ci.org/OctoMap/octomap_mapping)

Imported from SVN, see https://code.google.com/p/alufr-ros-pkg/ for the previous versions.

Modifications
==============

Modified in order to work with [rosbot_exploration](https://github.com/UCR-Robotics/rosbot_exploration) package.


## Installation
In your catkin workspace go to `/src` directory and clone this repository.
```
git clone https://github.com/acont017/octomap_mapping
```

After cloning the repository, `catkin_make` the workspace.

## Usage
In terminal run:
```
roslaunch octomap_server octomap_mapping.launch
```
