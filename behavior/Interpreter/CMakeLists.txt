cmake_minimum_required(VERSION 3.7)
project(Interpreter)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        context.cpp
        context.h
        interpret.cpp
        interpret.h
        main.cpp)

add_executable(Interpreter ${SOURCE_FILES})