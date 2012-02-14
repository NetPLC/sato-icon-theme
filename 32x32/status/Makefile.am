themedir = $(datadir)/icons/Sato/32x32/status
theme_DATA = audio-volume-high.png audio-volume-low.png audio-volume-medium.png audio-volume-mutted.png battery-charged.png battery-no-ac.png battery.png dialog-cancel.png dialog-ok.png
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd $(themedir) && $(ICONMAP) -c status )
MAINTAINERCLEANFILES = Makefile.in
