cmake_minimum_required(VERSION 3.0.0)
project(threadpool VERSION 0.1.0)

add_executable(${PROJECT_NAME} main.cpp)
target_link_libraries(${PROJECT_NAME} boost_system boost_thread pthread)