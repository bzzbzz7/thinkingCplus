cmake_minimum_required(VERSION 3.7)
project(Command)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Command.cpp
        Command.h
        Source.cpp)

add_executable(Command ${SOURCE_FILES})