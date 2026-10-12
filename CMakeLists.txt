cmake_minimum_required(VERSION 3.28.0)

find_package(Zephyr)

project(zephyr_template VERSION 0.1.0 LANGUAGES C)

target_sources(app PRIVATE src/main.c)

