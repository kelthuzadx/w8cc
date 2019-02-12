cmake_minimum_required(VERSION 3.5)
project(8cc-win)

set(SRC buffer.c cpp.c debug.c dict.c encoding.c error.c file.c
        gen.c lex.c main.c map.c parse.c path.c set.c vector.c)

add_executable(8cc-win ${SRC})