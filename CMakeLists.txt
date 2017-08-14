cmake_minimum_required(VERSION 3.8)
project(zebra)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp Evaluador.cpp Evaluador.h)
add_executable(zebra ${SOURCE_FILES})