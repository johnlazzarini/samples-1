cmake_minimum_required(VERSION 3.5)
project(06_simplePosixThreads)

#set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
add_definitions(-std=c99)

set(SOURCE_FILES thrd-posix.c)
add_executable(06_simplePosixThreads ${SOURCE_FILES})