dnl Copyright (C) 2015  Trevor Woerner <twoerner@gmail.com>

dnl AC_PREREQ(2.57)
AC_INIT([Qemu Scripts], 0.6.0, twoerner@gmail.com, qemu_scripts)
AC_CONFIG_SRCDIR(qstart_vm)
AM_INIT_AUTOMAKE([foreign no-dist-gzip dist-bzip2 1.9])

SUBDIRS="examples"

DOCBASEDIR="\$(DESTDIR)\$(datadir)/doc/\$(PACKAGE)-\$(VERSION)"
AC_SUBST(DOCBASEDIR)

dnl **********************************
dnl output
dnl **********************************
AC_OUTPUT(Makefile)
AC_OUTPUT(examples/Makefile)
