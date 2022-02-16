cmake_minimum_required(VERSION 3.20)
project(consoleApp)

set(CMAKE_CXX_STANDARD 14)

set(INC_DIR /Users/qqq/Documents/University/1 course/2 term/PBCT/1 lab/lib)
set(LINK_DIR /Users/qqq/Documents/University/1 course/2 term/PBCT/1 lab/lib/cmake-build-debug)

include_directories(${INC_DIR})
link_directories(${LINK_DIR})
link_libraries(MathFuncsLib)


add_executable(consoleApp MyExecRefsLib.cpp)


