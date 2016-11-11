cmake_minimum_required(VERSION 2.8.3)
project(bosch_hackathon_ros)


find_package(catkin REQUIRED COMPONENTS
        roscpp
        rospy
        std_msgs
        )

# include_directories(include)
include_directories(
        ${catkin_INCLUDE_DIRS}
)
