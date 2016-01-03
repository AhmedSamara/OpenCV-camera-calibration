cmake_minimum_required(VERSION 2.8)
project( calibration )
find_package( OpenCV REQUIRED )
add_executable( CalibrateCamera calibrate_camera.cpp )
target_link_libraries( CalibrateCamera ${OpenCV_LIBS} )

