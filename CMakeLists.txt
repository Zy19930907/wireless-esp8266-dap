# The following five lines of boilerplate have to be in your project's
# CMakeLists in this exact order for cmake to work correctly
cmake_minimum_required(VERSION 3.5)
#set(COMPONENT_DIRS "${IDF_PATH}/components ${PROJECT_PATH}/components")

include_directories(${CMAKE_CURRENT_SOURCE_DIR}/main)

include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project(esp8266_dap)
