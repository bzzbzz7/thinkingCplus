cmake_minimum_required(VERSION 3.7)
project(Prototype)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Prototype.cpp
        Prototype.h
        Source.cpp)

add_executable(Prototype ${SOURCE_FILES})