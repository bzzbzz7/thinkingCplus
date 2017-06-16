cmake_minimum_required(VERSION 3.7)
project(Strategy)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Source.cpp
        Strategy.cpp
        Strategy.h)

add_executable(Strategy ${SOURCE_FILES})