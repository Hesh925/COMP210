cmake_minimum_required(VERSION 3.27)
project(COMP_210 VERSION 1.0.0)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)
set(sourceFiles "main.cpp" "lib/utils/Utils.h")
add_subdirectory(lib/utils)

add_executable(${PROJECT_NAME} ${sourceFiles})