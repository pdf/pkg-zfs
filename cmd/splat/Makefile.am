include $(top_srcdir)/config/Rules.am

DEFAULT_INCLUDES += \
	-I$(top_srcdir)/include \
	-I$(top_srcdir)/lib/libcommon

sbin_PROGRAMS = splat

splat_SOURCES = splat.c
splat_LDFLAGS = $(top_builddir)/lib/libcommon/libcommon.la

EXTRA_DIST = splat.h
