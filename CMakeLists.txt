cmake_minimum_required(VERSION 3.28)
project(dropsource)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(dropsource
        dataobject.cpp
        dropsource.cpp
        enumformat.cpp
        main.cpp
        resource.h)
