cmake_minimum_required(VERSION 3.0.2)
project(com2009_odometry_example)

## Find catkin macros and libraries
find_package(catkin REQUIRED COMPONENTS
  geometry_msgs
  nav_msgs
  std_msgs
  rospy
)

###################################
## catkin specific configuration ##
###################################
catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES com2009_odometry_example
#  CATKIN_DEPENDS geometry_msgs nav_msgs rospy
#  DEPENDS system_lib
)

###########
## Build ##
###########

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)
