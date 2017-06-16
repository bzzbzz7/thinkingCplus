cmake_minimum_required(VERSION 3.7)
project(Visitor)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Source.cpp
        Visitor.cpp
        Visitor.h)

add_executable(Visitor ${SOURCE_FILES})