AUTOMAKE_OPTIONS=foreign

AM_CFLAGS = -I./include

#lib_LTLIBRARIES = lib/libadd.la
#lib_libadd_la_CFLAGS = -Os -I./include
#lib_libadd_la_SOURCES = src/add.c include/add.h


#bin_PROGRAMS = example/add_test
#example_add_test_CFLAGS = -Os -I./include
#example_add_test_SOURCES = example/add_test.c
#example_add_test_LDADD=lib/libadd.la

moduledir = $(prefix)
module_PROGRAMS = lib/add.so
lib_add_so_SOURCES = src/add.c
lib_add_so_LDFLAGS=-shared -fpic

noinst_LIBRARIES = lib/libadd.a
lib_libadd_a_CFLAGS = -Os -I./include
lib_libadd_a_SOURCES = src/add.c include/add.h
