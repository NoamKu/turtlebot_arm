cmake_minimum_required(VERSION 2.8.3)
project(mars_test)

find_package(catkin REQUIRED)

catkin_package()

install(PROGRAMS bin/arm_test.py DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION})
