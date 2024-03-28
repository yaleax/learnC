cmake_minimum_required(VERSION 3.27)
project(learnC)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(01)

add_executable(learnC
        01/main.c
        README.md)
