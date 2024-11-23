cmake_minimum_required(VERSION 3.5)

project (app)

add_executable(app src/main.cpp)

target_link_libraries(app PRIVATE src/polygame)