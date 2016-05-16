cmake_minimum_required(VERSION 3.3)
project(MLP)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp node.cpp node.h layer.cpp layer.h network.cpp network.h)
add_executable(MLP ${SOURCE_FILES})