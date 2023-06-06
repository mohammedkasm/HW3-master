cmake_minimum_required(VERSION 3.24)
project(HW3_master)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(HW3_master
        Queue.cpp
        Queue.h)
