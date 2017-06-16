cmake_minimum_required(VERSION 3.7)
project(Mediator)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Mediator.cpp
        Mediator.h
        Source.cpp)

add_executable(Mediator ${SOURCE_FILES})