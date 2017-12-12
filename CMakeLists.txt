cmake_minimum_required(VERSION 3.8)
project(Projet)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp Book.h Book.cpp Comic.h Comic.cpp Poetry.h)
add_executable(Projet ${SOURCE_FILES})