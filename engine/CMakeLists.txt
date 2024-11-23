cmake_minimum_required(VERSION 3.5)

project(polygame)

add_library(polygame STATIC
	src/engine.cpp
)

target_include_directories(polygame
    PUBLIC 
        ${PROJECT_SOURCE_DIR}/src
)