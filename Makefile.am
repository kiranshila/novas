ACLOCAL_AMFLAGS= -I m4

lib_LTLIBRARIES = libnovas.la
libnovas_la_LDFLAGS = -module -avoid-version -shared -no-undefined -export-dynamic -bundle -dynamiclib
libnovas_la_SOURCES = src/solsys1.c src/readeph0.c src/eph_manager.c src/nutation.c src/novascon.c src/novas.c
AUTOMAKE_OPTIONS = subdir-objects

include_HEADERS = src/eph_manager.h src/nutation.h src/novascon.h src/novas.h