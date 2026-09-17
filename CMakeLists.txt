cmake_minimum_required(VERSION 3.10.0)
project(hello_robomaster_mth VERSION 0.1.0 LANGUAGES C CXX)

set(CMAKE_CXX_STANDARD 17)
set (CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(hello_robomaster_mth src/main.cpp)
