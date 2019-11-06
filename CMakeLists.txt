cmake_minimum_required(VERSION 3.0.2)

project(procrank)

add_executable(procrank procrank.c pm_kernel.c pm_map.c pm_memusage.c pm_process.c strlcpy.c)

install(TARGETS procrank DESTINATION sbin)