cmake_minimum_required(VERSION 3.27)
project(text_editor LANGUAGES C)  # Specify that this is a C project

# Set the C standard, optional depending on your needs
set(CMAKE_C_STANDARD 99)  # or 11, 17, etc., depending on your requirements
set(CMAKE_C_STANDARD_REQUIRED True)

# Add the executable, change main.cpp to main.c
add_executable(text_editor main.c)






