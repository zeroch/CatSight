cmake_minimum_required(VERSION 3.0.0)
project(DisplayCamera)
find_package(OpenCV  REQUIRED)

add_executable(DisplayCamera objectDetection.cpp)
target_link_libraries(DisplayCamera ${OpenCV_LIBS})