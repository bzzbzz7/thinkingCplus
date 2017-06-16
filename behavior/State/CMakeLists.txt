cmake_minimum_required(VERSION 3.7)
project(State)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Source.cpp
        State.cpp
        State.h)

add_executable(State ${SOURCE_FILES})