cmake_minimum_required(VERSION 3.9)
project(proj1_starter_proj1_2)

set(CMAKE_CXX_STANDARD 11)

add_executable(proj1_starter_proj1_2
        input/combined.s
        input/comments.s
        input/imm.s
        input/labels.s
        input/p1_errors.s
        input/p2_errors.s
        input/pseudo.s
        input/simple.s
        link-in/linker1.out
        link-in/linker2.out
        link-in/linker3A.out
        link-in/linker3B.out
        link-out/ref/output1_ref
        link-out/ref/output2_ref
        link-out/ref/output3_ref
        linker-src/file_utils.s
        linker-src/linker.s
        linker-src/linker_utils.s
        linker-src/parsetools.s
        linker-src/string.s
        linker-src/symbol_list.s
        linker-tests/test_core.s
        linker-tests/test_linker_utils.s
        linker-tests/test_parsetools.s
        linker-tests/test_string.s
        linker-tests/test_symbol_list.s
        log/ref/p1_errors_ref.txt
        log/ref/p2_errors_ref.txt
        out/ref/combined_ref.int
        out/ref/combined_ref.out
        out/ref/comments_ref.int
        out/ref/comments_ref.out
        out/ref/imm_ref.int
        out/ref/imm_ref.out
        out/ref/labels_ref.int
        out/ref/labels_ref.out
        out/ref/pseduo_ref.int
        out/ref/pseudo_ref.int
        out/ref/pseudo_ref.out
        out/ref/simple_ref.int
        out/ref/simple_ref.out
        src/tables.c
        src/tables.h
        src/translate.c
        src/translate.h
        src/translate_utils.c
        src/translate_utils.h
        src/utils.c
        src/utils.h
        assembler.c
        assembler.h
        linker
        Makefile
        mars.jar
        run-valgrind
        test_assembler.c
        Test_link)
