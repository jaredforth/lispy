cmake_minimum_required(VERSION 3.0)
project (lispy)

include_directories(include)
include_directories(/usr/include/readline)

file(GLOB SOURCES "source/*.c")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -std=c99 -Wall")

add_executable(lispy ${SOURCES})
target_link_libraries(lispy readline)
