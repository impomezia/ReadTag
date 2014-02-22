cmake_minimum_required(VERSION 2.8)

project(ReadTag)

if (MSVC)
  set ( CMAKE_C_FLAGS_MINSIZEREL "-O1 -Os -MT")
  set ( CMAKE_CXX_FLAGS_MINSIZEREL "-O1 -Os -MT")
endif ()

add_subdirectory(ReadTag)
add_subdirectory(ReadTagDLL)