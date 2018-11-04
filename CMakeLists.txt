cmake_minimum_required(VERSION 2.8)

project( Li )

find_package( OpenCV REQUIRED )
include_directories( ${OpenCV_INCLUDE_DIRS} )


add_executable( ex stero.cpp )
target_link_libraries( ex ${OpenCV_LIBS} )


