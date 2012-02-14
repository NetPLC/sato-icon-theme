themedir = $(datadir)/icons/Sato/64x64/stock
theme_DATA = stock_person.png
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd $(DESTDIR)$(themedir) && $(ICONMAP) -c stock )
MAINTAINERCLEANFILES = Makefile.in
