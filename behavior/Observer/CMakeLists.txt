cmake_minimum_required(VERSION 3.7)
project(Observer)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Observer.cpp
        Observer.h
        Source.cpp)

add_executable(Observer ${SOURCE_FILES})