themedir = $(datadir)/icons/Sato/48x48/status
theme_DATA = ac-adaptor.png audio-volume-high.png audio-volume-low.png audio-volume-medium.png audio-volume-mutted.png battery-charged.png battery-charging-000.png battery-charging-020.png battery-charging-040.png battery-charging-060.png battery-charging-080.png battery-charging-100.png battery-discharging-000.png battery-discharging-020.png battery-discharging-040.png battery-discharging-060.png battery-discharging-080.png battery-discharging-100.png battery-no-ac.png battery.png dialog-cancel.png dialog-ok.png
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd $(DESTDIR)$(themedir) && $(ICONMAP) -c status )
MAINTAINERCLEANFILES = Makefile.in
