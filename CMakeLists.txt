cmake_minimum_required(VERSION 4.1)
project(lessons)

set(CMAKE_CXX_STANDARD 23)

add_executable(lessons main.cpp
        add.cpp
        convertation.cpp
        shop.cpp
        " ClothingStore.cpp"
        " GuessTheWord.cpp"
        ConsoleRPG.cpp)
