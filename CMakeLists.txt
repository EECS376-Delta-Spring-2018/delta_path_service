cmake_minimum_required(VERSION 2.8.3)
project(delta_path_service)

find_package(catkin_simple REQUIRED)

catkin_simple()

# Executables
cs_add_executable(delta_path_service src/delta_path_service.cpp)
cs_add_executable(delta_path_client src/delta_path_client.cpp)
cs_install()
cs_export()
    
