cmake_minimum_required(VERSION 3.5)

project(xrandr)

set (SRCS 
    xrandr.c
)

add_executable(xrandr ${SRCS})
target_link_libraries(xrandr X11 Xrandr m)