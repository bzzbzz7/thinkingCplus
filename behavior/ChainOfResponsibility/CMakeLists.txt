cmake_minimum_required(VERSION 3.7)
project(ChainOfResponsibility)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        handle.cpp
        handle.h
        main.cpp)

add_executable(ChainOfResponsibility ${SOURCE_FILES})