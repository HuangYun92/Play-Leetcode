cmake_minimum_required(VERSION 3.5)
project(cpp_0301)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main2.cpp)
add_executable(cpp_0301 ${SOURCE_FILES})