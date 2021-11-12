cmake_minimum_required (VERSION 3.8) 

project (cppcheck_project) 

include_directories( ${CMAKE_CURRENT_SOURCE_DIR}/src )          

add_executable (cppcheck_project "src/main.cc" "src/component1.cc")
