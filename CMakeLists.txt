cmake_minimum_required(VERSION 3.0)
project(ziptime)

add_executable(ziptime ZipEntry.cpp ZipFile.cpp ZipTime.cpp)
install(TARGETS ziptime DESTINATION bin)
