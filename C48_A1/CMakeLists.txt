cmake_minimum_required(VERSION 3.10)

project(A1)

find_package(OpenCV REQUIRED)

add_executable(a1 a1.cpp)

target_link_libraries(a1 ${OpenCV_LIBS})
