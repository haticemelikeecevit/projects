cmake_minimum_required(VERSION 3.8)
project(project1)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp Node.cpp Node.h LinkedList.cpp LinkedList.h Member.cpp Member.h SurveyClass.cpp SurveyClass.h)
add_executable(project1 ${SOURCE_FILES})