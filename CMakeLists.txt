cmake_minimum_required(VERSION 3.14)
project(_TSC_Laboratorio4_master)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(_TSC_Laboratorio4_master
        classes.h
        display_tools.h
        main.cpp
        math_tools.h
        sel.h
        tools.h)
