cmake_minimum_required(VERSION 3.7)
project(Template)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Source.cpp
        Template.cpp
        Template.h)

add_executable(Template ${SOURCE_FILES})