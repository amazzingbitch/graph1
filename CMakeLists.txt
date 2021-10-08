cmake_minimum_required(VERSION 3.19)
project(GRA1)

set(CMAKE_CXX_STANDARD 14)

add_executable(GRA1 main.cpp)

target_link_libraries(GRA1 -lOpenGL32 -lfreeGLUT -lGLU32)