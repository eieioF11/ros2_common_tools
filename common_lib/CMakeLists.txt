cmake_minimum_required(VERSION 3.8)
project(common_lib)

find_package(extension_ament REQUIRED)

extension_ament_init()

extension_ament_add_library(${PROJECT_NAME} INTERFACE)

extension_ament_final()