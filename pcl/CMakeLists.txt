cmake_minimum_required(VERSION 2.6)
project(pcl)

add_executable(pcl main.cpp)

install(TARGETS pcl RUNTIME DESTINATION bin)
