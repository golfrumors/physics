cmake_minimum_required(VERSION 3.25.1)
project(physics)

set(CMAKE_CXX_STANDARD 20)

add_executable(${PROJECT_NAME} src/main.cpp)

target_link_libraries(${PROJECT_NAME} SDL2main SDL2 GL)
