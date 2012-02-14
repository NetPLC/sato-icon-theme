themedir = $(datadir)/icons/Sato/64x64/places
theme_DATA = folder.png user-desktop.png
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd $(DESTDIR)$(themedir) && $(ICONMAP) -c places )
MAINTAINERCLEANFILES = Makefile.in
