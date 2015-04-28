## Copyright (C) 2015  Trevor Woerner <twoerner@gmail.com>

SUBDIRS =
EXTRA_DIST = cmds.txt \
	CONFIG.tumbleweed \
	CONFIG.gui \
	CONFIG.shared_folder \
	CONFIG.multiple_shared_folders

install-data-local:
	-$(mkdir_p) $(DOCBASEDIR)/examples
	-for file in $(EXTRA_DIST); do \
		$(INSTALL) $(srcdir)/$$file $(DOCBASEDIR)/examples; \
	done;
uninstall-local:
	$(RM) -fr $(DOCBASEDIR)/examples
