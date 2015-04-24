## Copyright (C) 2015  Trevor Woerner <twoerner@gmail.com>

########################
## scripts
########################
SUBDIRS = examples
ALLSCRIPTS = qstart_vm qnet_up qnet_down qnet_getip qrun_cmd
EXTRA_DIST = README
dist_bin_SCRIPTS = $(ALLSCRIPTS)
install-data-local:
	-$(mkdir_p) $(DOCBASEDIR)
	-$(INSTALL) $(srcdir)/README $(DOCBASEDIR)
uninstall-local:
	$(RM) -fr $(DOCBASEDIR)
CLEANFILES = $(ALLSCRIPTS) .doxygen
