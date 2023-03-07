cmake_minimum_required(VERSION 3.23)
project(StockManagementSystem)

set(CMAKE_CXX_STANDARD 14)

add_executable(StockManagementSystem main.cpp "Source/Item.cpp" "Header/Item.h")
