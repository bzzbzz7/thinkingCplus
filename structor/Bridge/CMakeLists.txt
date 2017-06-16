cmake_minimum_required(VERSION 3.7)
project(Bridge)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Bridge.cpp
        Bridge.h
        Source.cpp)

add_executable(Bridge ${SOURCE_FILES})