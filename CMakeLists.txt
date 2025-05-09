cmake_minimum_required(VERSION 2.8)
project(FRICP)

#--- CMake configuration
set(CMAKE_MODULE_PATH ${CMAKE_SOURCE_DIR}/cmake)

#--- Compiler configuration
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++14")