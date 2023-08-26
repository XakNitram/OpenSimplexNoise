cmake_minimum_required(VERSION 3.1)
project(OpenSimplexNoise VERSION 1.0.0 LANGUAGES C)

add_library(
    OpenSimplexNoise
    open-simplex-noise.h
    open-simplex-noise.c
)

target_include_directories(OpenSimplexNoise PUBLIC "${CMAKE_CURRENT_SOURCE_DIR}")
