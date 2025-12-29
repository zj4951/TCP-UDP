cmake_minimum_required(VERSION 3.16)
project(communicate)

set(CMAKE_CXX_STANDARD 11)

add_library(tcp tcp.cpp tcp.h)