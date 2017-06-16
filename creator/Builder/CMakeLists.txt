cmake_minimum_required(VERSION 3.7)
project(Builder)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Builder.cpp
        Builder.h
        BuilderMain.cpp)

add_executable(Builder ${SOURCE_FILES})