themedir = $(datadir)/icons/Sato/16x16/places
theme_DATA = folder.png user-desktop.png
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd $(DESTDIR)$(themedir) && $(ICONMAP) -c places )
MAINTAINERCLEANFILES = Makefile.in
