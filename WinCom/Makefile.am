## Process this file with Automake to create Makefile.in.

AUTOMAKE_OPTIONS = -Wno-portability
DOC := $(wildcard *.html)
MAK := $(wildcard *.dsp *.dsw *.bat)
WIN := $(wildcard *.rc *.ico *.h *.cpp)

EXTRA_DIST = \
	$(DOC) \
	$(MAK) \
	$(WIN)

SUBDIRS = hlp res
