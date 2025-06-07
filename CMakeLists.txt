cmake_minimum_required(VERSION 3.25)
project(Parallel_and_Distributed_Programming)

set(CMAKE_CXX_STANDARD 14)

include_directories(Dining-Philosophers-Problem)

add_executable(Parallel_and_Distributed_Programming
        Dining-Philosophers-Problem/dining_philosophers.cpp
        Dining-Philosophers-Problem/dining_philosophers.h)
