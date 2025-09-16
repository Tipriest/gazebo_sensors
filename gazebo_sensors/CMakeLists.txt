cmake_minimum_required(VERSION 3.0.2)
project(gazebo_sensors)

find_package(catkin REQUIRED COMPONENTS
  roscpp
  nav_msgs
  tf
)

catkin_package(
  CATKIN_DEPENDS roscpp nav_msgs tf
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)
