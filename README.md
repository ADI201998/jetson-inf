# jetson-inf
The package auto-trav was created as a ROS package and was used on NVIDIA's Jetson TX2. The sensors used were Intel RealSense D435, Garmin GPS 18x USB Sensor and LSM9DS0 IMU. The other packages which were used along with this and not included are [ros deep learning](https://github.com/dusty-nv/ros_deep_learning) (for tennis ball detection using deep learning) and [realsense](https://github.com/IntelRealSense/realsense-ros) (for using the RGB camera,depth image and point cloud from Intel RealSense D435 camera for tennis ball detection and obstacle avoidance).

The launch file auto.launch is used for the autonomous traversal task with obstacle avoidance done from point cloud data from the depth camera using [Point CLoud Library](http://pointclouds.org/documentation/).

The launch file ultra.launch is used for the autonomous traversal task with obstacle avoidance done from the RGB depth image from the depth camera using [OpenCV](https://docs.opencv.org/3.0-beta/doc/py_tutorials/py_tutorials.html/).
