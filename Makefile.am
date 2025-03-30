SUBDIRS = src

datadir = $(prefix)/share/myman

install-data-local:
	$(MKDIR_P) $(DESTDIR)$(datadir)/chr
	$(MKDIR_P) $(DESTDIR)$(datadir)/gfx
	$(MKDIR_P) $(DESTDIR)$(datadir)/sfx
	$(MKDIR_P) $(DESTDIR)$(datadir)/lvl
	$(MKDIR_P) $(DESTDIR)$(datadir)/spr
	cp -r $(srcdir)/chr/* $(DESTDIR)$(datadir)/chr/
	cp -r $(srcdir)/gfx/* $(DESTDIR)$(datadir)/gfx/
	cp -r $(srcdir)/sfx/* $(DESTDIR)$(datadir)/sfx/
	cp -r $(srcdir)/lvl/* $(DESTDIR)$(datadir)/lvl/
	cp -r $(srcdir)/spr/* $(DESTDIR)$(datadir)/spr/
