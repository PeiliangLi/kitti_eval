cmake_minimum_required(VERSION 2.8)
project( kitti_eval )
set(CMAKE_BUILD_TYPE "Release")
set(CMAKE_CXX_FLAGS "-std=c++11")
set(CMAKE_CXX_FLAGS_RELEASE "-O3 -Wall -g")


add_executable( eval evaluate_object_3d.cpp)
add_executable( eval_offline evaluate_object_3d_offline.cpp )
