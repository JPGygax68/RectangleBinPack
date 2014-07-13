cmake_minimum_required(VERSION 3.0)

project(RectangleBinPack)

add_library(RBP_Guillotine STATIC GuillotineBinPack.cpp GuillotineBinPack.h Rect.cpp Rect.h)

export(TARGETS RBP_Guillotine FILE RectangleBinPack-config.cmake)

export(PACKAGE ${PROJECT_NAME})
