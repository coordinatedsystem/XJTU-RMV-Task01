# 设置 CMake 最低版本要求
cmake_minimum_required(VERSION 3.10)

# 项目名称
project(HelloDXRMV)

# 指定 C++ 标准（这里使用 C++17）
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# 添加可执行文件，由 main.cpp 构建
add_executable(hello main.cpp)