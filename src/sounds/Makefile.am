EXTRA_DIST = autocannon.wav click.wav expl1.wav expl2.wav expl3.wav \
gunfire.wav highlight.wav

install-data-local:
	$(mkinstalldirs) $(DESTDIR)$(src_dir)/sounds
	@for file in $(EXTRA_DIST); do\
	  $(INSTALL_DATA) $(srcdir)/$$file $(DESTDIR)$(src_dir)/sounds/$$file;\
	done

