~~~
ign gazebo -v 4 /home/student/ws/src/dolly/dolly_ignition/models/tutorial_robot.sdf
ign topic -l
ign topic -e -t /imu/data
~~~

~~~
ros2 launch dolly_ignition tuto.launch.py
~~~