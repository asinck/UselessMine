lib_LTLIBRARIES = UselessMine.la

UselessMine_la_SOURCES = UselessMine.cpp
UselessMine_la_CXXFLAGS= -I$(top_srcdir)/include -I$(top_srcdir)/plugins/plugin_utils
UselessMine_la_LDFLAGS = -module -avoid-version -shared
UselessMine_la_LIBADD = $(top_builddir)/plugins/plugin_utils/libplugin_utils.la

AM_CPPFLAGS = $(CONF_CPPFLAGS)
AM_CFLAGS = $(CONF_CFLAGS)
AM_CXXFLAGS = $(CONF_CXXFLAGS)

EXTRA_DIST = \
	CHANGELOG.md \
	LICENSE.md \
	README.md \
	UselessMine.def \
	UselessMine.deathMessages

MAINTAINERCLEANFILES =	\
	Makefile.in
