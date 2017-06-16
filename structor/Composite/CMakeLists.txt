cmake_minimum_required(VERSION 3.7)
project(Composite)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Composite.cpp
        Composite.h
        Source.cpp)

add_executable(Composite ${SOURCE_FILES})