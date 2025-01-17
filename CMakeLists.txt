cmake_minimum_required(VERSION 3.10)

# Set the project name
project(cpp-12-aha-moments)

# Specify the C++ standard
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Set the output directory for the build
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR})

# Add the executable
add_executable(${PROJECT_NAME} main.cpp)
