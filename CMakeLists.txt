################################################################################
##                                    ctlepage
##
## This file is distributed under the 4-clause Berkeley Software Distribution
## License. See LICENSE for details.
################################################################################
cmake_minimum_required(VERSION 3.10)

project(ctlepage CXX)

list(APPEND CMAKE_MODULE_PATH ${CMAKE_SOURCE_DIR}/cmake)
include(Options)
include(UnitTest)

enable_unit_test()

add_subdirectory(src/ctlepage)
