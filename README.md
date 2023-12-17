<h2>Commands to launch</h2>

<h3>Point (1)</h3>
<code>roslaunch iiwa_gazebo iiwa_gazebo_circular_object.launch</code> (To run the circular object in Gazebo)<br>
<code>rosrun opencv_ros opencv_ros_node</code> (To run the circular objects recognition)<br>

<h3>Point (2a)</h3>

<code>roslaunch iiwa_gazebo iiwa_gazebo_aruco.launch</code> (To run the aruco in Gazebo and the _VelocityJointInterface_ controllers)<br>
<code>roslaunch aruco_ros usb_cam_aruco.launch camera:=/iiwa/camera1</code> (To run the aruco recognition)<br>
<code>rosrun kdl_ros_control kdl_robot_vision_control_2a ./src/iiwa_stack_cv/iiwa_description/urdf/iiwa14.urdf</code> (To run the controller)<br>

<h3>Point (2b)</h3>

<code>roslaunch iiwa_gazebo iiwa_gazebo_aruco.launch</code> (To run the aruco in Gazebo and the _VelocityJointInterface_ controllers)<br>
<code>roslaunch aruco_ros usb_cam_aruco.launch camera:=/iiwa/camera1</code> (To run the aruco recognition)<br>
<code>rosrun kdl_ros_control kdl_robot_vision_control_2b ./src/iiwa_stack_cv/iiwa_description/urdf/iiwa14.urdf</code> (To run the controller)<br>

<h3>Point (2c)</h3>

<code>roslaunch iiwa_gazebo iiwa_gazebo_effort_aruco.launch</code> (To run the aruco in Gazebo and the _EffortJointInterface_ controllers)<br>
<code>roslaunch aruco_ros usb_cam_aruco.launch camera:=/iiwa/camera1</code> (To run the aruco recognition)<br>
<code>rosrun kdl_ros_control kdl_robot_test ./src/iiwa_stack_cv/iiwa_description/urdf/iiwa14.urdf</code> (To run the controller)<br>
