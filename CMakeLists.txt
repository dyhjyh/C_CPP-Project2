cmake_minimum_required(VERSION 3.16)
project(project2)

set(CMAKE_CXX_STANDARD 11)

add_executable(project2 main.cpp calculate.cpp calculate.hpp preTreat.cpp preTreat.hpp)
