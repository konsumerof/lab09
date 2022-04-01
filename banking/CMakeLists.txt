cmake_minimum_required(VERSION 3.4)

set(CMAKE_CXX_STANDART 11)
set(CMAKE_CXX_STANDART_REQUIRES ON)

project(lib)

add_library(banking STATIC Account.cpp Transaction.cpp)
