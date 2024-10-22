cmake_minimum_required(VERSION 3.29)
project(UTP03-Task03-JNI)

set(CMAKE_CXX_STANDARD 20)

add_library(UTP03-Task03-JNI SHARED library.cpp)
