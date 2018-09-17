# AgriX
Development of an autonomous bot capable of cultivating and nurturing crops thereby aiding in indoor farming.

# Challenges:
To be able to navigate in an unknown environment autonomously and map the environment.

# 2D SLAM and gmapping:
We started with libfreenect package which is the most commonly used ROS package for retrieving pointcloud from the kinect sensor. Though there were some driver issue and few launch files weren't written as per our requirement, we modified it and obtained the pointcloud which we then used to obtain the 2D map.

# Odometry data integration:
Integrate odometry data using ROSPY lib for python, once it was done we had a 2D map of the indoor area that adapts dynamically to obstacles.

# Softwares and packages used:

## Robotic Operating System (aka) ROS:
ROS is the most reliable system architecture when it comes to the field of robotics and research. In this project everything runs around ROS from encoder data to the 2D map obatined from 2D SLAM.

## Kinect sensor (openni kinect):
Microsoft kinect is the go to piece of tech when it comes to depth sensing and we went for it without even hesitating and we're feeling good with the results it produced. We use it to fake a laserscan and use the pointcloud to make a 2D map of the indoor area.
