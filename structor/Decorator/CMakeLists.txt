cmake_minimum_required(VERSION 3.7)
project(Decorator)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Decorator.cpp
        Decorator.h
        Source.cpp)

add_executable(Decorator ${SOURCE_FILES})