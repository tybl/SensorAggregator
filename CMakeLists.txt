################################################################################
# License: The Unlicense (https://unlicense.org)
################################################################################
cmake_minimum_required(VERSION 3.14) # FetchContent_MakeAvailable

project(SensorAggregator
  VERSION 0.0.1
  DESCRIPTION "Tools to collect environment data"
  LANGUAGES CXX)

include(FetchContent)
include(util/cmake/CompilerSettings.cmake)
include(util/cmake/Linters.cmake)

