# $Id: Makefile.am 3783 2012-06-06 13:17:59Z mpip $

AM_CPPFLAGS = -I$(top_srcdir)/include

noinst_PROGRAMS = fastsumS2

fastsumS2_SOURCES = fastsumS2.c doxygen.h
fastsumS2_LDADD = $(top_builddir)/libnfft3.la

EXTRA_DIST = fastsumS2.m writeTestcase.m readTestcase.m README example.in example.out
