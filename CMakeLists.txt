cmake_minimum_required(VERSION 3.22.1)
project(CPP_Sample_Project)

include_directories(${CMAKE_CURRENT_SOURCE_DIR}/Analog Clock)

add_executable(${PROJECT_NAME} Analog_Clock.cpp)


