cmake_minimum_required (VERSION 3.18)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

set(CMAKE_SYSTEM_NAME Linux)
set(CMAKE_SYSTEM_PROCESSOR arm)

project(rm2-pdfkit CXX)

add_subdirectory(tpl/nlohmann-json)
add_subdirectory(tpl/spdlog)

add_subdirectory(src)
