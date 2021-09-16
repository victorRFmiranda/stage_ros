# stage_ros
A modified version of the Stage ROS simulator for Reinforcement Learning.

In this version, it is possible to change the robot's pose using a Pose topic:
'''
/cmd_pose
'''

Thus, in an RL training algorithm, it is possible to change the robot's pose without modifying the .world file and close the simulator.
