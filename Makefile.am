SUBDIRS=
INCLUDES=-I..

EXTRA_SOURCES= libcrow.spec libcrow.spec.in

lib_LTLIBRARIES=libcrow.la
libcrow_la_SOURCES =							\
	crow.h		crow.c
libcrow_la_LIBADD=
libcrow_la_LDFLAGS=

EXTRA_PROGRAMS=crow
crow_SOURCES=test.c
crow_LDFLAGS=libcrow.la

