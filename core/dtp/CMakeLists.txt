cmake_minimum_required(VERSION 3.0.2)
project(picarx_dtp)

find_package(catkin REQUIRED COMPONENTS
  roscpp
  rospy
  std_msgs
  picarx_msgs
)

catkin_package()

install(DIRECTORY launch
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
