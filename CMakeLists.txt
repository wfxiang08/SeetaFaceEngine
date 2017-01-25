cmake_minimum_required(VERSION 3.2)
project(SeetaFaceEngine)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

ADD_SUBDIRECTORY(FaceDetection)
ADD_SUBDIRECTORY(FaceAlignment)
ADD_SUBDIRECTORY(FaceIdentification)