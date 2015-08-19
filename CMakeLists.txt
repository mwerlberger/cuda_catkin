project(cuda_catkin)
cmake_minimum_required(VERSION 2.8.0)

find_package(catkin_simple REQUIRED)
catkin_simple()

cs_install()
cs_export(CFG_EXTRAS cuda_catkin.cmake)