cmake_minimum_required(VERSION 3.4)
project(formatter_ex)
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CURRENT_SOURCE_DIR /home/timur/BaltaevTimur/workspace/lab03hw/formatter_ex_lib/)
add_library(formatter_ex STATIC ${CMAKE_CURRENT_SOURCE_DIR}/formatter_ex.cpp)
include_directories(/home/timur/BaltaevTimur/workspace/lab03hw/formatter_lib/)
include_directories(${CMAKE_CURRENT_SOURSE_DIR}/formatter_ex.h)
