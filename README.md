#  AoyunTech Spot simulate
ayspot_a0_description

## Usage

Rviz:

	catkin_make

	source ~/catkin_ws/devel/setup.bash

	roslaunch urdf_tutorial display.launch model:='$(find ayspot_a0_description)/urdf/ayspot_a0.xacro'

or

	roslaunch ayspot_a0_description display.launch model:='$(find ayspot_a0_description)/urdf/ayspot_a0.xacro'


Gazebo:

	roslaunch ayspot_a0_description gazebo.launch
