cmake_minimum_required(VERSION 3.12)
project(MyCppProject)

# Set the C++ standard to C++17
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Specify the source files
set(SOURCES src/main.cpp)

# Define the target
add_executable(MyCppProject ${SOURCES})
