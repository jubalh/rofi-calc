ACLOCAL_AMFLAGS=-I m4
plugindir=${rofi_PLUGIN_INSTALL_DIR}/

plugin_LTLIBRARIES = calc.la

calc_la_SOURCES=\
		 src/calc.c

calc_la_CFLAGS= @glib_CFLAGS@ @rofi_CFLAGS@ @cairo_CFLAGS@
calc_la_LIBADD= @glib_LIBS@ @rofi_LIBS@ @cairo_LIBS@
calc_la_LDFLAGS= -module -avoid-version
