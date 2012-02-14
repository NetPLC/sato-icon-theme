themedir = $(datadir)/icons/Sato/22x22/places
theme_DATA = folder.png user-desktop.png
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd $(themedir) && $(ICONMAP) -c places )
MAINTAINERCLEANFILES = Makefile.in
