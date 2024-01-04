# cmake_minimum_required(VERSION 3.0)  # CMake最低版本要求

project(MyProject)  # 项目名称

# 添加可执行文件
add_executable(my_app src/main.cpp)

# 设置包含目录
target_include_directories(my_app PRIVATE include)

