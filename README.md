# ROS_Slam_and_gmapping
Implementation of SLAM and gmapping in a bot that autonomously maps an indoor area and moves to a given coordinate.

# Objective:
To be able to navigate in an unknown environment autonomously and map the environment which may be used for several applications, indoor farming in our case.

# Robotic Operating System (aka) ROS:
ROS is the most reliable system architecture when it comes to the field of robotics and research. In this project everything runs around ROS from encoder data to the 2D map obatined from 2D SLAM.

# Kinect sensor:
Microsoft kinect is the go to piece of tech when it comes to depth sensing and we went for it without even hesitating and we're feeling good with the results it produced. We use it to fake a laserscan and use the pointcloud to make a 2D map of the indoor area.

# 2D SLAM and gmapping:
We started with libfreenect package which is the most commonly used ROS package for retrieving pointcloud from the kinect sensor. Though there were some driver issue and few launch files weren't written as per our requirement, we modified it and obtained the pointcloud which we then used to obtain the 2D map.

# Odometry data integration:
We're yet to integrate the odometry data using ROSPY lib for python, once it is done we'll have a 2D map of the indoor area that behaves dynamically to obstacles.


