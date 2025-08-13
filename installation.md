## Installation

gedit code ali nano ~/.bashrc
Tam moraš nujno zapisati:

-source /opt/ros/humble/setup.bash 


-source /usr/share/colcon_argcomplete/hook/colcon-argcomplete.bash -> deloval ti bo <tab> pri colcon build ukazu
Colcon build -> dobiš build install in log direktorij

## ROS pkg create
ros2 pkg create <name_of_the_pkg> ---build-type ament_<python/cmake> --dependendcies <lib> <msg_type>

colcon build v src dir
## ROS launch file:
ros2 pkg create app_bringup --build-type ament_cmake



