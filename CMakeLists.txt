cmake_minimum_required(VERSION 3.4)

project(Hello-World)

SET(CMAKE_INCLUDE_CURRENT_DIR ON)

add_executable(${PROJECT_NAME}
    main.cpp
)
