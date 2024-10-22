cmake_minimum_required(VERSION 3.29)
project(UTP03-Task03-JNI)

set(CMAKE_CXX_STANDARD 20)

add_library(UTP03-Task03-JNI SHARED library.cpp)

target_include_directories(UTP03-Task03-JNI PRIVATE "C:/Program Files/Java/jdk-23/include")
target_include_directories(UTP03-Task03-JNI PRIVATE "C:/Program Files/Java/jdk-23/include/win32")
