cmake_minimum_required(VERSION 2.8.3)
project(bmv_ros)

find_package(catkin REQUIRED COMPONENTS
  rospy
  sensor_msgs
  std_msgs
)

catkin_package()
