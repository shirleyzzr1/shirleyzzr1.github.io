
SHELL = /bin/sh

# V=0 quiet, V=1 verbose.  other values don't work.
V = 0
Q1 = $(V:1=)
Q = $(Q1:0=@)
ECHO1 = $(V:1=@ :)
ECHO = $(ECHO1:0=@ echo)
NULLCMD = :

#### Start of system configuration section. ####

srcdir = .
topdir = /usr/include/ruby-2.7.0
hdrdir = $(topdir)
arch_hdrdir = /usr/include/x86_64-linux-gnu/ruby-2.7.0
PATH_SEPARATOR = :
VPATH = $(srcdir):$(arch_hdrdir)/ruby:$(hdrdir)/ruby
prefix = $(DESTDIR)/usr
rubysitearchprefix = $(sitearchlibdir)/$(RUBY_BASE_NAME)
rubyarchprefix = $(archlibdir)/$(RUBY_BASE_NAME)
rubylibprefix = $(libdir)/$(RUBY_BASE_NAME)
exec_prefix = $(prefix)
vendorarchhdrdir = $(sitearchincludedir)/$(RUBY_VERSION_NAME)/vendor_ruby
sitearchhdrdir = $(sitearchincludedir)/$(RUBY_VERSION_NAME)/site_ruby
rubyarchhdrdir = $(archincludedir)/$(RUBY_VERSION_NAME)
vendorhdrdir = $(rubyhdrdir)/vendor_ruby
sitehdrdir = $(rubyhdrdir)/site_ruby
rubyhdrdir = $(includedir)/$(RUBY_VERSION_NAME)
vendorarchdir = $(rubysitearchprefix)/vendor_ruby/$(ruby_version)
vendorlibdir = $(vendordir)/$(ruby_version)
vendordir = $(rubylibprefix)/vendor_ruby
sitearchdir = $(DESTDIR)./.gem.20211220-12956-xgutw6
sitelibdir = $(DESTDIR)./.gem.20211220-12956-xgutw6
sitedir = $(DESTDIR)/usr/local/lib/site_ruby
rubyarchdir = $(rubyarchprefix)/$(ruby_version)
rubylibdir = $(rubylibprefix)/$(ruby_version)
sitearchincludedir = $(includedir)/$(sitearch)
archincludedir = $(includedir)/$(arch)
sitearchlibdir = $(libdir)/$(sitearch)
archlibdir = $(libdir)/$(arch)
ridir = $(datarootdir)/$(RI_BASE_NAME)
mandir = $(datarootdir)/man
localedir = $(datarootdir)/locale
libdir = $(exec_prefix)/lib
psdir = $(docdir)
pdfdir = $(docdir)
dvidir = $(docdir)
htmldir = $(docdir)
infodir = $(datarootdir)/info
docdir = $(datarootdir)/doc/$(PACKAGE)
oldincludedir = $(DESTDIR)/usr/include
includedir = $(prefix)/include
runstatedir = $(DESTDIR)/var/run
localstatedir = $(DESTDIR)/var
sharedstatedir = $(prefix)/com
sysconfdir = $(DESTDIR)/etc
datadir = $(datarootdir)
datarootdir = $(prefix)/share
libexecdir = $(exec_prefix)/libexec
sbindir = $(exec_prefix)/sbin
bindir = $(exec_prefix)/bin
archdir = $(rubyarchdir)


CC_WRAPPER = 
CC = gcc
CXX = g++
LIBRUBY = $(LIBRUBY_SO)
LIBRUBY_A = lib$(RUBY_SO_NAME)-static.a
LIBRUBYARG_SHARED = -l$(RUBY_SO_NAME)
LIBRUBYARG_STATIC = -l$(RUBY_SO_NAME)-static $(MAINLIBS)
empty =
OUTFLAG = -o $(empty)
COUTFLAG = -o $(empty)
CSRCFLAG = $(empty)

RUBY_EXTCONF_H = 
cflags   = $(optflags) $(debugflags) $(warnflags)
cxxflags = 
optflags = -O3
debugflags = -ggdb3
warnflags = -Wall -Wextra -Wdeprecated-declarations -Wduplicated-cond -Wimplicit-function-declaration -Wimplicit-int -Wmisleading-indentation -Wpointer-arith -Wwrite-strings -Wimplicit-fallthrough=0 -Wmissing-noreturn -Wno-cast-function-type -Wno-constant-logical-operand -Wno-long-long -Wno-missing-field-initializers -Wno-overlength-strings -Wno-packed-bitfield-compat -Wno-parentheses-equality -Wno-self-assign -Wno-tautological-compare -Wno-unused-parameter -Wno-unused-value -Wsuggest-attribute=format -Wsuggest-attribute=noreturn -Wunused-variable
cppflags = 
CCDLFLAGS = -fPIC
CFLAGS   = $(CCDLFLAGS) -g -O2 -fdebug-prefix-map=/build/ruby2.7-QclakL/ruby2.7-2.7.0=. -fstack-protector-strong -Wformat -Werror=format-security -fPIC -std=c99 $(ARCH_FLAG)
INCFLAGS = -I. -I$(arch_hdrdir) -I$(hdrdir)/ruby/backward -I$(hdrdir) -I$(srcdir)
DEFS     = 
CPPFLAGS =  -Wdate-time -D_FORTIFY_SOURCE=2 $(DEFS) $(cppflags)
CXXFLAGS = $(CCDLFLAGS) -g -O2 -fdebug-prefix-map=/build/ruby2.7-QclakL/ruby2.7-2.7.0=. -fstack-protector-strong -Wformat -Werror=format-security $(ARCH_FLAG)
ldflags  = -L. -Wl,-Bsymbolic-functions -Wl,-z,relro -Wl,-z,now -fstack-protector-strong -rdynamic -Wl,-export-dynamic
dldflags = -Wl,-Bsymbolic-functions -Wl,-z,relro -Wl,-z,now 
ARCH_FLAG = 
DLDFLAGS = $(ldflags) $(dldflags) $(ARCH_FLAG)
LDSHARED = $(CC) -shared
LDSHAREDXX = $(CXX) -shared
AR = ar
EXEEXT = 

RUBY_INSTALL_NAME = $(RUBY_BASE_NAME)2.7
RUBY_SO_NAME = ruby-2.7
RUBYW_INSTALL_NAME = 
RUBY_VERSION_NAME = $(RUBY_BASE_NAME)-$(ruby_version)
RUBYW_BASE_NAME = rubyw
RUBY_BASE_NAME = ruby

arch = x86_64-linux-gnu
sitearch = $(arch)
ruby_version = 2.7.0
ruby = $(bindir)/$(RUBY_BASE_NAME)2.7
RUBY = $(ruby)
ruby_headers = $(hdrdir)/ruby.h $(hdrdir)/ruby/backward.h $(hdrdir)/ruby/ruby.h $(hdrdir)/ruby/defines.h $(hdrdir)/ruby/missing.h $(hdrdir)/ruby/intern.h $(hdrdir)/ruby/st.h $(hdrdir)/ruby/subst.h $(arch_hdrdir)/ruby/config.h

RM = rm -f
RM_RF = $(RUBY) -run -e rm -- -rf
RMDIRS = rmdir --ignore-fail-on-non-empty -p
MAKEDIRS = /bin/mkdir -p
INSTALL = /usr/bin/install -c
INSTALL_PROG = $(INSTALL) -m 0755
INSTALL_DATA = $(INSTALL) -m 644
COPY = cp
TOUCH = exit >

#### End of system configuration section. ####

preload = 
libpath = . $(archlibdir)
LIBPATH =  -L. -L$(archlibdir)
DEFFILE = 

CLEANFILES = mkmf.log
DISTCLEANFILES = 
DISTCLEANDIRS = 

extout = 
extout_prefix = 
target_prefix = /commonmarker
LOCAL_LIBS = 
LIBS = $(LIBRUBYARG_SHARED)  -lm   -lc
ORIG_SRCS = arena.c autolink.c blocks.c buffer.c cmark.c cmark_ctype.c commonmark.c commonmarker.c core-extensions.c ext_scanners.c footnotes.c houdini_href_e.c houdini_html_e.c houdini_html_u.c html.c inlines.c iterator.c latex.c linked_list.c man.c map.c node.c plaintext.c plugin.c references.c registry.c render.c scanners.c strikethrough.c syntax_extension.c table.c tagfilter.c utf8.c xml.c
SRCS = $(ORIG_SRCS) 
OBJS = arena.o autolink.o blocks.o buffer.o cmark.o cmark_ctype.o commonmark.o commonmarker.o core-extensions.o ext_scanners.o footnotes.o houdini_href_e.o houdini_html_e.o houdini_html_u.o html.o inlines.o iterator.o latex.o linked_list.o man.o map.o node.o plaintext.o plugin.o references.o registry.o render.o scanners.o strikethrough.o syntax_extension.o table.o tagfilter.o utf8.o xml.o
HDRS = $(srcdir)/cmark-gfm-extension_api.h $(srcdir)/map.h $(srcdir)/tagfilter.h $(srcdir)/autolink.h $(srcdir)/inlines.h $(srcdir)/syntax_extension.h $(srcdir)/parser.h $(srcdir)/scanners.h $(srcdir)/buffer.h $(srcdir)/node.h $(srcdir)/cmark_ctype.h $(srcdir)/utf8.h $(srcdir)/registry.h $(srcdir)/html.h $(srcdir)/references.h $(srcdir)/commonmarker.h $(srcdir)/config.h $(srcdir)/ext_scanners.h $(srcdir)/cmark-gfm-core-extensions.h $(srcdir)/table.h $(srcdir)/cmark-gfm_version.h $(srcdir)/chunk.h $(srcdir)/footnotes.h $(srcdir)/plugin.h $(srcdir)/houdini.h $(srcdir)/cmark-gfm.h $(srcdir)/iterator.h $(srcdir)/strikethrough.h $(srcdir)/cmark-gfm-extensions_export.h $(srcdir)/cmark-gfm_export.h $(srcdir)/render.h
LOCAL_HDRS = 
TARGET = commonmarker
TARGET_NAME = commonmarker
TARGET_ENTRY = Init_$(TARGET_NAME)
DLLIB = $(TARGET).so
EXTSTATIC = 
STATIC_LIB = 

TIMESTAMP_DIR = .
BINDIR        = $(bindir)
RUBYCOMMONDIR = $(sitedir)$(target_prefix)
RUBYLIBDIR    = $(sitelibdir)$(target_prefix)
RUBYARCHDIR   = $(sitearchdir)$(target_prefix)
HDRDIR        = $(rubyhdrdir)/ruby$(target_prefix)
ARCHHDRDIR    = $(rubyhdrdir)/$(arch)/ruby$(target_prefix)
TARGET_SO_DIR =
TARGET_SO     = $(TARGET_SO_DIR)$(DLLIB)
CLEANLIBS     = $(TARGET_SO) 
CLEANOBJS     = *.o  *.bak

all:    $(DLLIB)
static: $(STATIC_LIB)
.PHONY: all install static install-so install-rb
.PHONY: clean clean-so clean-static clean-rb

clean-static::
clean-rb-default::
clean-rb::
clean-so::
clean: clean-so clean-static clean-rb-default clean-rb
		-$(Q)$(RM) $(CLEANLIBS) $(CLEANOBJS) $(CLEANFILES) .*.time

distclean-rb-default::
distclean-rb::
distclean-so::
distclean-static::
distclean: clean distclean-so distclean-static distclean-rb-default distclean-rb
		-$(Q)$(RM) Makefile $(RUBY_EXTCONF_H) conftest.* mkmf.log
		-$(Q)$(RM) core ruby$(EXEEXT) *~ $(DISTCLEANFILES)
		-$(Q)$(RMDIRS) $(DISTCLEANDIRS) 2> /dev/null || true

realclean: distclean
install: install-so install-rb

install-so: $(DLLIB) $(TIMESTAMP_DIR)/.sitearchdir.-.commonmarker.time
	$(INSTALL_PROG) $(DLLIB) $(RUBYARCHDIR)
clean-static::
	-$(Q)$(RM) $(STATIC_LIB)
install-rb: pre-install-rb do-install-rb install-rb-default
install-rb-default: pre-install-rb-default do-install-rb-default
pre-install-rb: Makefile
pre-install-rb-default: Makefile
do-install-rb:
do-install-rb-default:
pre-install-rb-default:
	@$(NULLCMD)
$(TIMESTAMP_DIR)/.sitearchdir.-.commonmarker.time:
	$(Q) $(MAKEDIRS) $(@D) $(RUBYARCHDIR)
	$(Q) $(TOUCH) $@

site-install: site-install-so site-install-rb
site-install-so: install-so
site-install-rb: install-rb

.SUFFIXES: .c .m .cc .mm .cxx .cpp .o .S

.cc.o:
	$(ECHO) compiling $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -c $(CSRCFLAG)$<

.cc.S:
	$(ECHO) translating $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -S $(CSRCFLAG)$<

.mm.o:
	$(ECHO) compiling $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -c $(CSRCFLAG)$<

.mm.S:
	$(ECHO) translating $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -S $(CSRCFLAG)$<

.cxx.o:
	$(ECHO) compiling $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -c $(CSRCFLAG)$<

.cxx.S:
	$(ECHO) translating $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -S $(CSRCFLAG)$<

.cpp.o:
	$(ECHO) compiling $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -c $(CSRCFLAG)$<

.cpp.S:
	$(ECHO) translating $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -S $(CSRCFLAG)$<

.c.o:
	$(ECHO) compiling $(<)
	$(Q) $(CC) $(INCFLAGS) $(CPPFLAGS) $(CFLAGS) $(COUTFLAG)$@ -c $(CSRCFLAG)$<

.c.S:
	$(ECHO) translating $(<)
	$(Q) $(CC) $(INCFLAGS) $(CPPFLAGS) $(CFLAGS) $(COUTFLAG)$@ -S $(CSRCFLAG)$<

.m.o:
	$(ECHO) compiling $(<)
	$(Q) $(CC) $(INCFLAGS) $(CPPFLAGS) $(CFLAGS) $(COUTFLAG)$@ -c $(CSRCFLAG)$<

.m.S:
	$(ECHO) translating $(<)
	$(Q) $(CC) $(INCFLAGS) $(CPPFLAGS) $(CFLAGS) $(COUTFLAG)$@ -S $(CSRCFLAG)$<

$(TARGET_SO): $(OBJS) Makefile
	$(ECHO) linking shared-object commonmarker/$(DLLIB)
	-$(Q)$(RM) $(@)
	$(Q) $(LDSHARED) -o $@ $(OBJS) $(LIBPATH) $(DLDFLAGS) $(LOCAL_LIBS) $(LIBS)



$(OBJS): $(HDRS) $(ruby_headers)
