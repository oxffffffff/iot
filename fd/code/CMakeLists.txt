cmake_minimum_required(VERSION 2.8)
project( fd )
find_package( OpenCV REQUIRED )
add_executable( fd main.cpp )
target_link_libraries( fd ${OpenCV_LIBS} )