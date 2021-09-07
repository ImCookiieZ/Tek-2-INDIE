cmake_minimum_required(VERSION 3.16)
project(cross_plattform)

set(CMAKE_CXX_STANDARD 14)
FILE(GLOB lib_dir "src/*.cpp")
add_executable(cross_platform ${lib_dir})