## Articubot_one

Run:
~~~
ros2 launch articubot_one launch_robot.launch.new.py
~~~

Run teleop:
~~~
ros2 run teleop_twist_keyboard teleop_twist_keyboard --ros-args -r /cmd_vel:=/diff_cont/cmd_vel_unstamped
~~~

---
## Diffdrive_arduino
~~~
ros2 launch diffdrive_arduino diffbot.launch.py
~~~