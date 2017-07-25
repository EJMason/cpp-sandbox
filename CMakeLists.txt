cmake_minimum_required(VERSION 3.7)
project(cpp_sandbox)

set(CMAKE_CXX_STANDARD 14)

set(SOURCE_FILES main.cpp helpers.cpp helpers.h)
add_executable(cpp_sandbox ${SOURCE_FILES})