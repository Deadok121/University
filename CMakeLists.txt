cmake_minimum_required(VERSION 3.13)
project(queue)

set(CMAKE_CXX_STANDARD 17)

add_executable(queue main.cpp Node.h cmake-build-debug/Queue_Impl.cpp)