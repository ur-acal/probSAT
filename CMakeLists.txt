cmake_minimum_required(VERSION 3.10)

project(probSAT)

set(CMAKE_CXX_STANDARD 11)


set(CMAKE_C_COMPILER "gcc")
set(CMAKE_CXX_COMPILER "g++")

add_executable(probSAT probSAT.c)
target_link_options(probSAT BEFORE PRIVATE  -lm)
