ADD_LIBRARY(capture freenect.cpp freenect.hpp)
TARGET_INCLUDE_DIRECTORIES(capture PUBLIC ${CMAKE_CURRENT_SOURCE_DIR} ${LIBUSB_1_INCLUDE_DIRS} ${FREENECT_INCLUDE_DIRS} ${OpenCV2_INCLUDE_DIRS})