project( LineOdroid )
find_package( OpenCV REQUIRED )
add_executable( LineOdroid LineOdroid.cpp )
target_link_libraries( LineOdroid  ${OpenCV_LIBS} )
