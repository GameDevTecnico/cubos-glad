cmake_minimum_required(VERSION 3.20.0)
project(glad)

add_library(glad INTERFACE)
target_sources(glad INTERFACE src/glad.c)
target_include_directories(glad INTERFACE include)
