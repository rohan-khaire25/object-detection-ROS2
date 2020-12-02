# object-detection-ROS2
Object detection in ROS2 using opencv

### objectives ###
detect objects using OpenCv in ankhbot robot.

### How to use ###
* Clone the respository in `**src** folder of ROS2 workspace.
* Build the files using ``colcon build`` command.
* Run the object detection node in a terminal using the command: ``ros2 run object_detection detector``
* In a terminal, type ``ros2 launch ankhbot_gazebo ankhbot.launch.py world:=ankhbot_city.world``.
* Change the topic in Rviz in Image tab to ``/object_detection/output`` to visualize the detected objects.
