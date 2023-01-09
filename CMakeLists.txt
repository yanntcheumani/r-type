cmake_minimum_required(VERSION 3.24)
project(rtype)

set(CMAKE_CXX_STANDARD 20)

include_directories(include)

set(SRC_CLIENT src/client/main.cpp)
set(SRC_SERVER src/client/main.cpp)

add_executable(r-type_server ${SRC_SERVER})
add_executable(r-type_client ${SRC_CLIENT})
