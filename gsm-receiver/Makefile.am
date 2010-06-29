include $(top_srcdir)/Makefile.common

ACLOCAL_AMFLAGS = -Iconfig

SUBDIRS = src config
DIST_SUBDIRS = src config

EXTRA_DIST = \
	configure		\
	gsm-receiver.pc.in	\
	config.h.in
#	bootstrap		

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = gsm-receiver.pc
