themedir = $(datadir)/icons/Sato/16x16/actions
theme_DATA = gtk-add.png gtk-fullscreen.png gtk-go-back-ltr.png gtk-go-down.png gtk-go-forward-ltr.png gtk-go-up.png gtk-open.png gtk-remove.png gtk-zoom-in.png gtk-zoom-out.png media-playback-pause.png media-playback-start.png media-playback-stop.png media-record.png media-seek-backward.png media-seek-forward.png media-skip-backward.png media-skip-forward.png system-restart.png system-shutdown.png system-suspend.png
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd $(DESTDIR)$(themedir) && $(ICONMAP) -c actions )
MAINTAINERCLEANFILES = Makefile.in
