themedir = $(datadir)/icons/Sato/16x16/devices
theme_DATA = media-flash-cf.png media-flash.png media-flash-sd.png
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd $(DESTDIR)$(themedir) && $(ICONMAP) -c devices )
MAINTAINERCLEANFILES = Makefile.in
