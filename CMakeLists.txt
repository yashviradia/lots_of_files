cmake_minimum_required(VERSION 3.26)
project(lots_of_files)

set(CMAKE_CXX_STANDARD 17)

add_executable(lots_of_files main.cpp
        functions.cpp
        functions.h)
