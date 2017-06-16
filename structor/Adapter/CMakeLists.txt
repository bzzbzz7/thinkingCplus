cmake_minimum_required(VERSION 3.7)
project(Adapter)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Adapter.cpp
        Adapter.h
        main.cpp)

add_executable(Adapter ${SOURCE_FILES})