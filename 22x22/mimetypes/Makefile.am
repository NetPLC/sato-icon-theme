themedir = $(datadir)/icons/Sato/22x22/mimetypes
theme_DATA = application-x-executable.png image-x-generic.png text-x-generic.png x-office-address-book.png x-office-calendar.png x-office-todo.png
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd $(DESTDIR)$(themedir) && $(ICONMAP) -c mimetypes )
MAINTAINERCLEANFILES = Makefile.in
