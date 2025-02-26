cmake_minimum_required(VERSION 3.5)

project(hello)

set (CMAKE_CXX_STANDARD 11)

#add_subdirectory(xxx)

set(MEMBER_SOURCES
	hello.cpp
)

add_executable(hello ${MEMBER_SOURCES})

install(TARGETS hello)
