cmake_minimum_required(VERSION 3.7)
project(Facade)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Facade.cpp
        Facade.h
        Source.cpp)

add_executable(Facade ${SOURCE_FILES})