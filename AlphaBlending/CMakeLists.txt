cmake_minimum_required(VERSION 3.13)
project(alphaBlend)
find_package(OpenCV REQUIRED)
include_directories(${OpenCV_INCLUDE_DIRS})
add_executable(alphaBlend alphaBlend.cpp)
target_link_libraries(alphaBlend ${OpenCV_LIBS})
