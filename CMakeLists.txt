cmake_minimum_required(VERSION 3.18)
project(ybot-geode)

find_package(Geode REQUIRED)
geode_add_mod(${PROJECT_NAME}
    SOURCES src/YBot.cpp
    HEADERS include/YBot.hpp
)
