cmake_minimum_required(VERSION 3.5)
set(EXTRA_COMPONENT_DIRS ../../components esp32-camera static_images)
include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project(person_detection)
