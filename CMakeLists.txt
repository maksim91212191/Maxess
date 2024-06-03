set(CMAKE_TRY_COMPILE_TARGET_TYPE "STATIC_LIBRARY")
project(maxess)

cmake_minimum_required(VERSION 3.12)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

set(SOURCES 
    main.cpp
)

# set (HEADERS
# )

add_executable(${PROJECT_NAME} ${SOURCES})