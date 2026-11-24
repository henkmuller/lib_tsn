cmake_minimum_required(VERSION 3.21)
include($ENV{XMOS_CMAKE_PATH}/xcommon.cmake)
project(lib_tsn_examples)

# Only AN01032 is built from the top level for now. AN00202 and AN00203
# still use their original build files and are not added here.
add_subdirectory(examples/AN01032_100Mbit_avb_i2s_demo)
