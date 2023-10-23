cmake_minimum_required(VERSION 3.26)
project(Cpp)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fmodules-ts")
# Enable the module experiment
set(CMAKE_EXPERIMENTAL_CXX_MODULE_DYNDEP ON)
add_executable(Cpp main.cpp
        employee.cppm
)
