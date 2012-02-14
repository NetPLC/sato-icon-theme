themedir = $(datadir)/icons/Sato/22x22/apps
theme_DATA = accessories-text-editor.png applications-games.png audio-player.png contacts.png dates.png file-manager.png im-client.png nm-connecting.png nm-device-wired.png nm-no-connection.png nm-signal-00.png nm-signal-100.png nm-signal-25.png nm-signal-50.png nm-signal-75.png preferences-desktop-theme.png preferences-system.png sync.png tasks.png task-switcher.png utilities-terminal.png video-player.png voice-call.png web-browser.png
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd $(DESTDIR)$(themedir) && $(ICONMAP) -c apps )
MAINTAINERCLEANFILES = Makefile.in
