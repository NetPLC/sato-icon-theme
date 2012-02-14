themedir = $(datadir)/icons/Sato/16x16/apps
theme_DATA = accessories-text-editor.png applications-games.png audio-player.png contacts.png dates.png file-manager.png im-client.png preferences-desktop-theme.png preferences-system.png sync.png tasks.png task-switcher.png utilities-terminal.png video-player.png voice-call.png web-browser.png
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd $(DESTDIR)$(themedir) && $(ICONMAP) -c apps )
MAINTAINERCLEANFILES = Makefile.in
