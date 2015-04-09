ACLOCAL_AMFLAGS = -I m4 ${ACLOCAL_FLAGS}
DISTCHECK_CONFIGURE_FLAGS = --enable-introspection

SUBDIRS = m4 gnt

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = gnt.pc

EXTRA_DIST = \
	m4/introspection.m4 \
	gnt.pc.in
