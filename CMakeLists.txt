cmake_minimum_required(VERSION 3.0.0)
project(hello VERSION 0.1.0)

# c++ complile options 
set(CMAKE_CXX_STANDARD 17)
enable_language(CXX)

add_executable(hello  
    main.cpp
)