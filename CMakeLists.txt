cmake_minimum_required(VERSION 3.0)

# set the project name
project(Test)

set (SOURCE_DIR ${CMAKE_CURRENT_SOURCE_DIR}/src)

# add the executable
add_executable(Test ${SOURCE_DIR}/Test_1.c)