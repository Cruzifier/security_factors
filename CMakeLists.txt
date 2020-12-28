cmake_minimum_required(VERSION 3.9)
project(security_factors)

set(CMAKE_CXX_STANDARD 14)
set(SOURCE_FILES main.cpp cand_elim.cpp)

add_executable(security_factors ${SOURCE_FILES})