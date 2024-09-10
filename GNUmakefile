all:	Makefile
	$(MAKE) -f $<
%:	Makefile
	$(MAKE) -f $< $*
Makefile:
	./autogen.sh
	./configure --prefix=$(HOME)/usr
