cmake_minimum_required(VERSION 3.7)
project(Flyweight)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Flyweight.cpp
        Flyweight.h
        Source.cpp)

add_executable(Flyweight ${SOURCE_FILES})