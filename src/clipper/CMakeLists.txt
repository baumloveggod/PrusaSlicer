cmake_minimum_required(VERSION 3.5)
project(clipper)

add_library(clipper STATIC
# We are using ClipperLib compiled as part of the libslic3r project using Slic3r::Point as its base type.
#    clipper.cpp
#    clipper.hpp
    clipper_z.cpp
    clipper_z.hpp
)

target_link_libraries(clipper PRIVATE TBB::tbb TBB::tbbmalloc int128)
target_link_libraries(clipper PUBLIC Eigen3::Eigen)
target_include_directories(clipper PUBLIC .)
