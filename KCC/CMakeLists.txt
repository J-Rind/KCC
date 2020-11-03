cmake_minimum_required(VERSION 3.17)
project(KCC C)

set(CMAKE_C_STANDARD 11)

add_executable(KCC main.c systemdefs.h)