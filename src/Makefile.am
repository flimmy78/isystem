## Process this file with automake to produce Makefile.in

## Created by Anjuta

AUTOMAKE_OPTIONS = subdir-objects

AM_CPPFLAGS = \
	-DPACKAGE_LOCALE_DIR=\""$(localedir)"\" \
	-DPACKAGE_SRC_DIR=\""$(srcdir)"\" \
	-DPACKAGE_DATA_DIR=\""$(pkgdatadir)"\" \
	$(ISYSTEM_CFLAGS)

AM_CFLAGS =\
	 -Wall\
	 -g

bindir = $(prefix)/isystem
bin_PROGRAMS = isystem

isystem_SOURCES = \
	utils/memmap.c \
	isystem_event_handler.c \
	isystem.c \
	main.c

isystem_LDFLAGS = 

isystem_LDADD = $(ISYSTEM_LIBS)


SUBDIRS = \
	config \
	vtoold
