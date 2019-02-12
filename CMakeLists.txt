cmake_minimum_required(VERSION 3.5)
project(w8cc)

set(SRC src/buffer.c src/cpp.c src/debug.c src/dict.c src/encoding.c src/error.c src/file.c
        src/gen.c src/lex.c src/main.c src/map.c src/parse.c src/path.c src/set.c src/vector.c)

add_executable(w8cc ${SRC})