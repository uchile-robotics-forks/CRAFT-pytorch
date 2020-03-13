cmake_minimum_required(VERSION 2.8.3)
project(craft)

find_package(catkin)

catkin_python_setup()

catkin_package(
  LIBRARIES craft
)

install(
  PROGRAMS
    
  DESTINATION
    ${CATKIN_PACKAGE_BIN_DESTINATION}
)
