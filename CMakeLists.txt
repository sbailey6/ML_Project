cmake_minimum_required(VERSION 3.10)
project(ML_Project)

set(CMAKE_CXX_FLAGS "-Wall -Wextra -pedantic")

set(Sources Test.cpp)
set(Headers Test.cpp)

set(CMAKE_CXX_STANDARD 17)

add_executable(Test ${Sources})