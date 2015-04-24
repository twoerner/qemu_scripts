## Copyright (C) 2015  Trevor Woerner <twoerner@gmail.com>

SUBDIRS =
EXTRA_DIST = cmds.txt \
	CONFIG.tumbleweed \
	CONFIG.gui \
	CONFIG.shared_folder

install-data-local:
	-$(mkdir_p) $(DOCBASEDIR)/examples
	-for file in $(EXTRA_DIST); do \
		$(INSTALL) $(srcdir)/$$file $(DOCBASEDIR)/examples; \
	done;
uninstall-local:
	$(RM) -fr $(DOCBASEDIR)/examples
