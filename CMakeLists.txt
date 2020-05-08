cmake_minimum_required(VERSION 3.16)
project(MiniProject)

set(CMAKE_CXX_STANDARD 14)

add_executable(MiniProject application.cpp)
target_link_libraries(MiniProject glfw GLEW rt m dl GL GLU)