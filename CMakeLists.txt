cmake_minimum_required(VERSION 4.2)
project(gloop)

set(CMAKE_CXX_STANDARD 14)

include_directories(include)

add_executable(gloop
        include/gloop.h
        src/gloop.cpp)
