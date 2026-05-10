cmake_minimum_required(VERSION 4.3.2)
set(CMAKE_CXX_STANDARD 20)
project(HelloWorld)

add_executable(HelloWorldExe main.cpp)
add_subdirectory(src/)
target_link_libraries(HelloWorldExe HelloLib)

