cmake_minimum_required(VERSION 3.10)

project(server-lesson-1 C)

add_executable(server server.c erproc.c)
add_executable(client client.c erproc.c)
