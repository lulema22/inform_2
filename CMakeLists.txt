cmake_minimum_required(VERSION 3.10)

project(tmp_pohyi)

# Устанавливаем стандарт языка
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

set(SOURCE_FILES
        main_1.cpp
        ArraySequenceNew.h
        DynamicArrayNew.h
        ListSequenceNew.h
        SequenceNew.h
        ArraySequenceNew.h
        DynamicArrayNew.h
        ListSequenceNew.h
        SequenceNew.h
        Person.h
        ZipUnzip.h
        Deck.h
        tmp_1.cpp
        main_2.cpp
        MutableImmutableDek.h
)


add_executable(tmp_pohyi ${SOURCE_FILES})


