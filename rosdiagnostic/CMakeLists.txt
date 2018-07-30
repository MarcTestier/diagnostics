cmake_minimum_required(VERSION 3.5)
project(rosdiagnostic)

# Support C++14
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++14")

#find_package(catkin REQUIRED)

# catkin_package()

catkin_python_setup()


ament_package()
