cmake_minimum_required(VERSION 3.16)
project(semaphores C)

set(CMAKE_C_STANDARD 99)

add_executable(queue queue/queue_sem.c utility/utils.c sem/sem.c)

