Lab 5 Contents
=================================================


bag
--------
Contains the ROS bag file with stored point cloud data.

config
--------
Contains the RViz config file referenced from the launch file.

launch
--------
Contains the launch file. Arguments:
* **use_imu:** when set, use the new XACRO file, navviswimu.xacro.  Otherwise, use navvis.xacro.  Default true.
* **use\_sim\_time:** When set, adds the /use_sim_time parameter to use the external Gazebo clock.  Default true.
* **use\_robot\_state\_publisher:**  Whether to launch a robot\_state\_publisher node.  Default true.
* **filename:** for using custom XACRO file.  default depends on if use\_imu is set.

In addition to the functions listed above, the launch file will always launch joint\_state\_publisher and rviz with the config file saved in the config directory.

models
--------

Contains the two XACRO files, one from the previous lab, navvis.xacro, and one with the added base_link and imu links, navviswimu.xacro.

screenshot
--------
For storing screenshots of package functionality.

The Readme
----------
You are here.
