themedir = $(datadir)/icons/Sato/64x64/apps
theme_DATA = accessories-text-editor.png applications-games.png audio-player.png contacts.png dates.png file-manager.png im-client.png panel-task-switcher.png panel-user-desktop.png preferences-desktop-theme.png preferences-system.png sync.png tasks.png utilities-terminal.png video-player.png voice-call.png web-browser.png
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd $(DESTDIR)$(themedir) && $(ICONMAP) -c apps )
MAINTAINERCLEANFILES = Makefile.in
