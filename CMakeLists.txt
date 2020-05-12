cmake_minimum_required(VERSION 3.14)
project(spin_err C)

set(CMAKE_C_STANDARD 99)

add_executable(spin_err main.c mythread.h)