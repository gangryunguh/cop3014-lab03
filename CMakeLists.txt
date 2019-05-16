cmake_minimum_required(VERSION 3.08)
project(cop3014_lab03)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES batavg.cpp bill.cpp righttrig.cpp tabledata.cpp)

add_executable(batavg.exe batavg.cpp)
add_executable(bill.exe bill.cpp)
add_executable(righttrig.exe righttrig.cpp)
add_executable(tabledata.exe tabledata.cpp)


