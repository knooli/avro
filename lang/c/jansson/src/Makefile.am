noinst_HEADERS = jansson.h

noinst_LTLIBRARIES = libjansson.la
libjansson_la_SOURCES = \
	dump.c \
	hashtable.c \
	hashtable.h \
	jansson_private.h \
	load.c \
	strbuffer.c \
	strbuffer.h \
	utf.c \
	utf.h \
	util.h \
	value.c
libjansson_la_LDFLAGS = \
	-export-symbols-regex '^json_' \
	-version-info 1:2:1

AM_CFLAGS = -Wall -Wextra -Werror
