ACLOCAL_AMFLAGS = -I m4
AUTOMAKE_OPTIONS = subdir-objects
bin_PROGRAMS = test_c
test_c_SOURCES = main.cpp

@DX_RULES@

EXTRA_DIST = \
	autogen.sh \
	README.md \
	$(DX_CONFIG)

MOSTLYCLEANFILES = $(DX_CLEANFILES)

if MAKE_MAN

dist_man3_MANS = $(top_builddir)/doc/man/man3/*.3
$(dist_man3_MANS): doxygen-doc

endif
