themedir = $(datadir)/icons/Sato/48x48/actions
theme_DATA = gtk-add.png gtk-fullscreen.png gtk-go-back-ltr.png gtk-go-down.png gtk-go-forward-ltr.png gtk-go-up.png gtk-media-playback-pause.png gtk-media-playback-start.png gtk-media-record.png gtk-media-seek-backward.png gtk-media-seek-forward.png gtk-media-stop.png gtk-open.png gtk-remove.png gtk-zoom-in.png gtk-zoom-out.png system-restart.png system-shutdown.png system-suspend.png
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd $(DESTDIR)$(themedir) && $(ICONMAP) -c actions )
MAINTAINERCLEANFILES = Makefile.in
