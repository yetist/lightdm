ACLOCAL_AMFLAGS = -I m4
SUBDIRS = common liblightdm-gobject liblightdm-qt
if COMPILE_TESTS
SUBDIRS += tests
endif
SUBDIRS += data po src doc help

DISTCHECK_CONFIGURE_FLAGS = --enable-introspection --enable-gtk-doc

EXTRA_DIST = \
	autogen.sh \
	lightdm.doap \
	COPYING.GPL3 \
	COPYING.LGPL2 \
	COPYING.LGPL3 \
	NEWS
