cmake_minimum_required(VERSION 2.8.12.2)
project(GLEW C)


include_directories(${CMAKE_CURRENT_SOURCE_DIR}/include)

add_library(glew STATIC src/glew.c include/GL/glew.h)
