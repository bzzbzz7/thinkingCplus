cmake_minimum_required(VERSION 3.7)
project(Singleton)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
    Singleton.cpp
    Singleton.h
    SingletonMain.cpp)

add_executable(Singleton ${SOURCE_FILES})