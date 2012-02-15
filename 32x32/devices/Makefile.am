themedir = $(datadir)/icons/Sato/32x32/devices
theme_DATA = drive-harddisk.png media-flash-cf.png media-flash.png media-flash-sd.png
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd $(DESTDIR)$(themedir) && $(ICONMAP) -c devices )
MAINTAINERCLEANFILES = Makefile.in
