cmake_minimum_required(VERSION 3.22)
project(solver_lib)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_library(solver_lib STATIC solver.cpp)

target_include_directories(solver_lib PUBLIC
    ${CMAKE_CURRENT_SOURCE_DIR}
)
