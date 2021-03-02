cmake_minimum_required(VERSION 3.16)
project(mpi_test C)

set(CMAKE_C_STANDARD 11)

include_directories(/usr/lib/x86_64-linux-gnu/openmpi/include/)
add_executable(mpi_test main.c)