cmake_minimum_required(VERSION 3.25)

project(cjson LANGUAGES C)

add_library(cjson STATIC
    "cJSON.c"
    "cJSON_Utils.c"
)

target_include_directories(cjson PUBLIC .)
