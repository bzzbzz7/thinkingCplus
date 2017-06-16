cmake_minimum_required(VERSION 3.7)
project(Iterator)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Iterator.cpp
        Iterator.h
        Source.cpp)

add_executable(Iterator ${SOURCE_FILES})