cmake_minimum_required(VERSION 3.7)
project(Proxy)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Proxy.cpp
        Proxy.h
        Source.cpp)

add_executable(Proxy ${SOURCE_FILES})