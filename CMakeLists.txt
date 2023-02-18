cmake_minimum_required(VERSION 3.6)

project(Hello)

set(SOURCE src/hello.cpp)

add_executable(${PROJECT_NAME} ${SOURCE})

enable_testing()
add_subdirectory(test)
