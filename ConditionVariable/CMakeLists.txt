cmake_minimum_required(VERSION 3.6)
project(ConditionVariable)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(ConditionVariable ${SOURCE_FILES})
add_executable(inappropriateunlock inappropriateunlock.cpp)