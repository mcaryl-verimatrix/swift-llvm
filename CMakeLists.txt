cmake_minimum_required(VERSION 3.12)

project(test)
set(Python_FIND_STRATEGY VERSION 3.8)
find_package(Python3 REQUIRED COMPONENTS Interpreter)