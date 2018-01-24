cmake_minimum_required(VERSION 2.6)
project(pcl)

find_package(PCL)

include_directories(${PCL_INCLUDE_DIRS})
add_executable(pcl main.cpp)
target_link_libraries(pcl ${PCL_LIBS})

install(TARGETS pcl RUNTIME DESTINATION bin)
