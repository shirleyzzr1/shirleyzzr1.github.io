
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
sitearchdir = $(DESTDIR)./.gem.20211115-8664-1egrzqv
sitelibdir = $(DESTDIR)./.gem.20211115-8664-1egrzqv
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
CFLAGS   = $(CCDLFLAGS) -g -O2 -fdebug-prefix-map=/build/ruby2.7-QclakL/ruby2.7-2.7.0=. -fstack-protector-strong -Wformat -Werror=format-security -fPIC  -g -DXP_UNIX -Wall -Wcast-qual -Wwrite-strings -Wmissing-noreturn -Winline -DNOKOGIRI_USE_PACKAGED_LIBRARIES $(ARCH_FLAG)
INCFLAGS = -I. -I$(arch_hdrdir) -I$(hdrdir)/ruby/backward -I$(hdrdir) -I$(srcdir)
DEFS     = 
CPPFLAGS = -DHAVE_XMLPARSEDOC -DHAVE_XSLTPARSESTYLESHEETDOC -DHAVE_EXSLTFUNCREGISTER -DHAVE_XMLHASFEATURE -DHAVE_XMLFIRSTELEMENTCHILD -DHAVE_XMLRELAXNGSETPARSERSTRUCTUREDERRORS -DHAVE_XMLRELAXNGSETPARSERSTRUCTUREDERRORS -DHAVE_XMLRELAXNGSETVALIDSTRUCTUREDERRORS -DHAVE_XMLSCHEMASETVALIDSTRUCTUREDERRORS -DHAVE_XMLSCHEMASETPARSERSTRUCTUREDERRORS -I/home/shirley/myblog/jekyll-theme-massively-master/vendor/bundle/ruby/2.7.0/gems/nokogiri-1.10.1/ports/x86_64-pc-linux-gnu/libxslt/1.1.33/include -I/home/shirley/myblog/jekyll-theme-massively-master/vendor/bundle/ruby/2.7.0/gems/nokogiri-1.10.1/ports/x86_64-pc-linux-gnu/libxml2/2.9.9/include/libxml2 -I/home/shirley/myblog/jekyll-theme-massively-master/vendor/bundle/ruby/2.7.0/gems/nokogiri-1.10.1/ports/x86_64-pc-linux-gnu/libxml2/2.9.9/include/libxml2 -Wdate-time -D_FORTIFY_SOURCE=2 $(DEFS) $(cppflags) "-DNOKOGIRI_LIBXML2_PATH=\"/home/shirley/myblog/jekyll-theme-massively-master/vendor/bundle/ruby/2.7.0/gems/nokogiri-1.10.1/ports/x86_64-pc-linux-gnu/libxml2/2.9.9\"" "-DNOKOGIRI_LIBXML2_PATCHES=\"0001-Revert-Do-not-URI-escape-in-server-side-includes.patch\"" "-DNOKOGIRI_LIBXSLT_PATH=\"/home/shirley/myblog/jekyll-theme-massively-master/vendor/bundle/ruby/2.7.0/gems/nokogiri-1.10.1/ports/x86_64-pc-linux-gnu/libxslt/1.1.33\"" "-DNOKOGIRI_LIBXSLT_PATCHES=\"\""
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
libpath = . $(archlibdir) /home/shirley/myblog/jekyll-theme-massively-master/vendor/bundle/ruby/2.7.0/gems/nokogiri-1.10.1/ports/x86_64-pc-linux-gnu/libxml2/2.9.9/lib /home/shirley/myblog/jekyll-theme-massively-master/vendor/bundle/ruby/2.7.0/gems/nokogiri-1.10.1/ports/x86_64-pc-linux-gnu/libxslt/1.1.33/lib
LIBPATH =  -L. -L$(archlibdir) -L/home/shirley/myblog/jekyll-theme-massively-master/vendor/bundle/ruby/2.7.0/gems/nokogiri-1.10.1/ports/x86_64-pc-linux-gnu/libxml2/2.9.9/lib -L/home/shirley/myblog/jekyll-theme-massively-master/vendor/bundle/ruby/2.7.0/gems/nokogiri-1.10.1/ports/x86_64-pc-linux-gnu/libxslt/1.1.33/lib
DEFFILE = 

CLEANFILES = mkmf.log
DISTCLEANFILES = 
DISTCLEANDIRS = 

extout = 
extout_prefix = 
target_prefix = /nokogiri
LOCAL_LIBS = 
LIBS = $(LIBRUBYARG_SHARED) /home/shirley/myblog/jekyll-theme-massively-master/vendor/bundle/ruby/2.7.0/gems/nokogiri-1.10.1/ports/x86_64-pc-linux-gnu/libxslt/1.1.33/lib/libexslt.a -lm -ldl -llzma -lz /home/shirley/myblog/jekyll-theme-massively-master/vendor/bundle/ruby/2.7.0/gems/nokogiri-1.10.1/ports/x86_64-pc-linux-gnu/libxml2/2.9.9/lib/libxml2.a /home/shirley/myblog/jekyll-theme-massively-master/vendor/bundle/ruby/2.7.0/gems/nokogiri-1.10.1/ports/x86_64-pc-linux-gnu/libxslt/1.1.33/lib/libxslt.a -ldl -lm -llzma -lz /home/shirley/myblog/jekyll-theme-massively-master/vendor/bundle/ruby/2.7.0/gems/nokogiri-1.10.1/ports/x86_64-pc-linux-gnu/libxml2/2.9.9/lib/libxml2.a -llzma -lm   -lc 
ORIG_SRCS = html_document.c html_element_description.c html_entity_lookup.c html_sax_parser_context.c html_sax_push_parser.c nokogiri.c xml_attr.c xml_attribute_decl.c xml_cdata.c xml_comment.c xml_document.c xml_document_fragment.c xml_dtd.c xml_element_content.c xml_element_decl.c xml_encoding_handler.c xml_entity_decl.c xml_entity_reference.c xml_io.c xml_libxml2_hacks.c xml_namespace.c xml_node.c xml_node_set.c xml_processing_instruction.c xml_reader.c xml_relax_ng.c xml_sax_parser.c xml_sax_parser_context.c xml_sax_push_parser.c xml_schema.c xml_syntax_error.c xml_text.c xml_xpath_context.c xslt_stylesheet.c
SRCS = $(ORIG_SRCS) 
OBJS = html_document.o html_element_description.o html_entity_lookup.o html_sax_parser_context.o html_sax_push_parser.o nokogiri.o xml_attr.o xml_attribute_decl.o xml_cdata.o xml_comment.o xml_document.o xml_document_fragment.o xml_dtd.o xml_element_content.o xml_element_decl.o xml_encoding_handler.o xml_entity_decl.o xml_entity_reference.o xml_io.o xml_libxml2_hacks.o xml_namespace.o xml_node.o xml_node_set.o xml_processing_instruction.o xml_reader.o xml_relax_ng.o xml_sax_parser.o xml_sax_parser_context.o xml_sax_push_parser.o xml_schema.o xml_syntax_error.o xml_text.o xml_xpath_context.o xslt_stylesheet.o
HDRS = $(srcdir)/xml_processing_instruction.h $(srcdir)/xml_node.h $(srcdir)/xml_document_fragment.h $(srcdir)/xml_node_set.h $(srcdir)/html_sax_parser_context.h $(srcdir)/xml_comment.h $(srcdir)/xml_xpath_context.h $(srcdir)/xslt_stylesheet.h $(srcdir)/xml_attr.h $(srcdir)/xml_reader.h $(srcdir)/xml_sax_push_parser.h $(srcdir)/html_entity_lookup.h $(srcdir)/xml_schema.h $(srcdir)/xml_entity_reference.h $(srcdir)/xml_sax_parser_context.h $(srcdir)/xml_io.h $(srcdir)/xml_syntax_error.h $(srcdir)/xml_document.h $(srcdir)/xml_dtd.h $(srcdir)/html_document.h $(srcdir)/xml_cdata.h $(srcdir)/xml_element_content.h $(srcdir)/xml_text.h $(srcdir)/xml_encoding_handler.h $(srcdir)/xml_libxml2_hacks.h $(srcdir)/xml_entity_decl.h $(srcdir)/html_element_description.h $(srcdir)/xml_sax_parser.h $(srcdir)/xml_attribute_decl.h $(srcdir)/html_sax_push_parser.h $(srcdir)/xml_relax_ng.h $(srcdir)/xml_element_decl.h $(srcdir)/nokogiri.h $(srcdir)/xml_namespace.h
LOCAL_HDRS = 
TARGET = nokogiri
TARGET_NAME = nokogiri
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

install-so: $(DLLIB) $(TIMESTAMP_DIR)/.sitearchdir.-.nokogiri.time
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
$(TIMESTAMP_DIR)/.sitearchdir.-.nokogiri.time:
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
	$(ECHO) linking shared-object nokogiri/$(DLLIB)
	-$(Q)$(RM) $(@)
	$(Q) $(LDSHARED) -o $@ $(OBJS) $(LIBPATH) $(DLDFLAGS) $(LOCAL_LIBS) $(LIBS)



###
html_document.o: html_document.c html_document.h nokogiri.h xml_io.h	\
  xml_document.h html_entity_lookup.h xml_node.h xml_text.h		\
  xml_cdata.h xml_attr.h xml_processing_instruction.h			\
  xml_entity_reference.h xml_document_fragment.h xml_comment.h		\
  xml_node_set.h xml_dtd.h xml_attribute_decl.h xml_element_decl.h	\
  xml_entity_decl.h xml_xpath_context.h xml_element_content.h		\
  xml_sax_parser_context.h xml_sax_parser.h xml_sax_push_parser.h	\
  xml_reader.h html_sax_parser_context.h xslt_stylesheet.h		\
  xml_syntax_error.h xml_schema.h xml_relax_ng.h			\
  html_element_description.h xml_namespace.h xml_encoding_handler.h

html_element_description.o: html_element_description.c			\
 html_element_description.h nokogiri.h xml_io.h xml_document.h		\
 html_entity_lookup.h html_document.h xml_node.h xml_text.h		\
 xml_cdata.h xml_attr.h xml_processing_instruction.h			\
 xml_entity_reference.h xml_document_fragment.h xml_comment.h		\
 xml_node_set.h xml_dtd.h xml_attribute_decl.h xml_element_decl.h	\
 xml_entity_decl.h xml_xpath_context.h xml_element_content.h		\
 xml_sax_parser_context.h xml_sax_parser.h xml_sax_push_parser.h	\
 xml_reader.h html_sax_parser_context.h xslt_stylesheet.h		\
 xml_syntax_error.h xml_schema.h xml_relax_ng.h xml_namespace.h		\
 xml_encoding_handler.h

html_entity_lookup.o: html_entity_lookup.c html_entity_lookup.h		\
  nokogiri.h xml_io.h xml_document.h html_document.h xml_node.h		\
  xml_text.h xml_cdata.h xml_attr.h xml_processing_instruction.h	\
  xml_entity_reference.h xml_document_fragment.h xml_comment.h		\
  xml_node_set.h xml_dtd.h xml_attribute_decl.h xml_element_decl.h	\
  xml_entity_decl.h xml_xpath_context.h xml_element_content.h		\
  xml_sax_parser_context.h xml_sax_parser.h xml_sax_push_parser.h	\
  xml_reader.h html_sax_parser_context.h xslt_stylesheet.h		\
  xml_syntax_error.h xml_schema.h xml_relax_ng.h			\
  html_element_description.h xml_namespace.h xml_encoding_handler.h

html_sax_parser_context.o: html_sax_parser_context.c			\
 html_sax_parser_context.h nokogiri.h xml_io.h xml_document.h		\
 html_entity_lookup.h html_document.h xml_node.h xml_text.h		\
 xml_cdata.h xml_attr.h xml_processing_instruction.h			\
 xml_entity_reference.h xml_document_fragment.h xml_comment.h		\
 xml_node_set.h xml_dtd.h xml_attribute_decl.h xml_element_decl.h	\
 xml_entity_decl.h xml_xpath_context.h xml_element_content.h		\
 xml_sax_parser_context.h xml_sax_parser.h xml_sax_push_parser.h	\
 xml_reader.h xslt_stylesheet.h xml_syntax_error.h xml_schema.h		\
 xml_relax_ng.h html_element_description.h xml_namespace.h		\
 xml_encoding_handler.h

nokogiri.o: nokogiri.c nokogiri.h xml_io.h xml_document.h		\
  html_entity_lookup.h html_document.h xml_node.h xml_text.h		\
  xml_cdata.h xml_attr.h xml_processing_instruction.h			\
  xml_entity_reference.h xml_document_fragment.h xml_comment.h		\
  xml_node_set.h xml_dtd.h xml_attribute_decl.h xml_element_decl.h	\
  xml_entity_decl.h xml_xpath_context.h xml_element_content.h		\
  xml_sax_parser_context.h xml_sax_parser.h xml_sax_push_parser.h	\
  xml_reader.h html_sax_parser_context.h xslt_stylesheet.h		\
  xml_syntax_error.h xml_schema.h xml_relax_ng.h			\
  html_element_description.h xml_namespace.h xml_encoding_handler.h

xml_attr.o: xml_attr.c xml_attr.h nokogiri.h xml_io.h xml_document.h	\
  html_entity_lookup.h html_document.h xml_node.h xml_text.h		\
  xml_cdata.h xml_processing_instruction.h xml_entity_reference.h	\
  xml_document_fragment.h xml_comment.h xml_node_set.h xml_dtd.h	\
  xml_attribute_decl.h xml_element_decl.h xml_entity_decl.h		\
  xml_xpath_context.h xml_element_content.h xml_sax_parser_context.h	\
  xml_sax_parser.h xml_sax_push_parser.h xml_reader.h			\
  html_sax_parser_context.h xslt_stylesheet.h xml_syntax_error.h	\
  xml_schema.h xml_relax_ng.h html_element_description.h		\
  xml_namespace.h xml_encoding_handler.h

xml_attribute_decl.o: xml_attribute_decl.c xml_attribute_decl.h		\
  nokogiri.h xml_io.h xml_document.h html_entity_lookup.h		\
  html_document.h xml_node.h xml_text.h xml_cdata.h xml_attr.h		\
  xml_processing_instruction.h xml_entity_reference.h			\
  xml_document_fragment.h xml_comment.h xml_node_set.h xml_dtd.h	\
  xml_element_decl.h xml_entity_decl.h xml_xpath_context.h		\
  xml_element_content.h xml_sax_parser_context.h xml_sax_parser.h	\
  xml_sax_push_parser.h xml_reader.h html_sax_parser_context.h		\
  xslt_stylesheet.h xml_syntax_error.h xml_schema.h xml_relax_ng.h	\
  html_element_description.h xml_namespace.h xml_encoding_handler.h

xml_cdata.o: xml_cdata.c xml_cdata.h nokogiri.h xml_io.h		\
  xml_document.h html_entity_lookup.h html_document.h xml_node.h	\
  xml_text.h xml_attr.h xml_processing_instruction.h			\
  xml_entity_reference.h xml_document_fragment.h xml_comment.h		\
  xml_node_set.h xml_dtd.h xml_attribute_decl.h xml_element_decl.h	\
  xml_entity_decl.h xml_xpath_context.h xml_element_content.h		\
  xml_sax_parser_context.h xml_sax_parser.h xml_sax_push_parser.h	\
  xml_reader.h html_sax_parser_context.h xslt_stylesheet.h		\
  xml_syntax_error.h xml_schema.h xml_relax_ng.h			\
  html_element_description.h xml_namespace.h xml_encoding_handler.h

xml_comment.o: xml_comment.c xml_comment.h nokogiri.h xml_io.h		\
  xml_document.h html_entity_lookup.h html_document.h xml_node.h	\
  xml_text.h xml_cdata.h xml_attr.h xml_processing_instruction.h	\
  xml_entity_reference.h xml_document_fragment.h xml_node_set.h		\
  xml_dtd.h xml_attribute_decl.h xml_element_decl.h xml_entity_decl.h	\
  xml_xpath_context.h xml_element_content.h xml_sax_parser_context.h	\
  xml_sax_parser.h xml_sax_push_parser.h xml_reader.h			\
  html_sax_parser_context.h xslt_stylesheet.h xml_syntax_error.h	\
  xml_schema.h xml_relax_ng.h html_element_description.h		\
  xml_namespace.h xml_encoding_handler.h

xml_document.o: xml_document.c xml_document.h nokogiri.h xml_io.h	\
  html_entity_lookup.h html_document.h xml_node.h xml_text.h		\
  xml_cdata.h xml_attr.h xml_processing_instruction.h			\
  xml_entity_reference.h xml_document_fragment.h xml_comment.h		\
  xml_node_set.h xml_dtd.h xml_attribute_decl.h xml_element_decl.h	\
  xml_entity_decl.h xml_xpath_context.h xml_element_content.h		\
  xml_sax_parser_context.h xml_sax_parser.h xml_sax_push_parser.h	\
  xml_reader.h html_sax_parser_context.h xslt_stylesheet.h		\
  xml_syntax_error.h xml_schema.h xml_relax_ng.h			\
  html_element_description.h xml_namespace.h xml_encoding_handler.h

xml_document_fragment.o: xml_document_fragment.c			\
  xml_document_fragment.h nokogiri.h xml_io.h xml_document.h		\
  html_entity_lookup.h html_document.h xml_node.h xml_text.h		\
  xml_cdata.h xml_attr.h xml_processing_instruction.h			\
  xml_entity_reference.h xml_comment.h xml_node_set.h xml_dtd.h		\
  xml_attribute_decl.h xml_element_decl.h xml_entity_decl.h		\
  xml_xpath_context.h xml_element_content.h xml_sax_parser_context.h	\
  xml_sax_parser.h xml_sax_push_parser.h xml_reader.h			\
  html_sax_parser_context.h xslt_stylesheet.h xml_syntax_error.h	\
  xml_schema.h xml_relax_ng.h html_element_description.h		\
  xml_namespace.h xml_encoding_handler.h

xml_dtd.o: xml_dtd.c xml_dtd.h nokogiri.h xml_io.h xml_document.h	\
  html_entity_lookup.h html_document.h xml_node.h xml_text.h		\
  xml_cdata.h xml_attr.h xml_processing_instruction.h			\
  xml_entity_reference.h xml_document_fragment.h xml_comment.h		\
  xml_node_set.h xml_attribute_decl.h xml_element_decl.h		\
  xml_entity_decl.h xml_xpath_context.h xml_element_content.h		\
  xml_sax_parser_context.h xml_sax_parser.h xml_sax_push_parser.h	\
  xml_reader.h html_sax_parser_context.h xslt_stylesheet.h		\
  xml_syntax_error.h xml_schema.h xml_relax_ng.h			\
  html_element_description.h xml_namespace.h xml_encoding_handler.h

xml_element_content.o: xml_element_content.c xml_element_content.h	\
  nokogiri.h xml_io.h xml_document.h html_entity_lookup.h		\
  html_document.h xml_node.h xml_text.h xml_cdata.h xml_attr.h		\
  xml_processing_instruction.h xml_entity_reference.h			\
  xml_document_fragment.h xml_comment.h xml_node_set.h xml_dtd.h	\
  xml_attribute_decl.h xml_element_decl.h xml_entity_decl.h		\
  xml_xpath_context.h xml_sax_parser_context.h xml_sax_parser.h		\
  xml_sax_push_parser.h xml_reader.h html_sax_parser_context.h		\
  xslt_stylesheet.h xml_syntax_error.h xml_schema.h xml_relax_ng.h	\
  html_element_description.h xml_namespace.h xml_encoding_handler.h

xml_element_decl.o: xml_element_decl.c xml_element_decl.h nokogiri.h	\
  xml_io.h xml_document.h html_entity_lookup.h html_document.h		\
  xml_node.h xml_text.h xml_cdata.h xml_attr.h				\
  xml_processing_instruction.h xml_entity_reference.h			\
  xml_document_fragment.h xml_comment.h xml_node_set.h xml_dtd.h	\
  xml_attribute_decl.h xml_entity_decl.h xml_xpath_context.h		\
  xml_element_content.h xml_sax_parser_context.h xml_sax_parser.h	\
  xml_sax_push_parser.h xml_reader.h html_sax_parser_context.h		\
  xslt_stylesheet.h xml_syntax_error.h xml_schema.h xml_relax_ng.h	\
  html_element_description.h xml_namespace.h xml_encoding_handler.h

xml_encoding_handler.o: xml_encoding_handler.c xml_encoding_handler.h	\
  nokogiri.h xml_io.h xml_document.h html_entity_lookup.h		\
  html_document.h xml_node.h xml_text.h xml_cdata.h xml_attr.h		\
  xml_processing_instruction.h xml_entity_reference.h			\
  xml_document_fragment.h xml_comment.h xml_node_set.h xml_dtd.h	\
  xml_attribute_decl.h xml_element_decl.h xml_entity_decl.h		\
  xml_xpath_context.h xml_element_content.h xml_sax_parser_context.h	\
  xml_sax_parser.h xml_sax_push_parser.h xml_reader.h			\
  html_sax_parser_context.h xslt_stylesheet.h xml_syntax_error.h	\
  xml_schema.h xml_relax_ng.h html_element_description.h		\
  xml_namespace.h

xml_entity_decl.o: xml_entity_decl.c xml_entity_decl.h nokogiri.h	\
  xml_io.h xml_document.h html_entity_lookup.h html_document.h		\
  xml_node.h xml_text.h xml_cdata.h xml_attr.h				\
  xml_processing_instruction.h xml_entity_reference.h			\
  xml_document_fragment.h xml_comment.h xml_node_set.h xml_dtd.h	\
  xml_attribute_decl.h xml_element_decl.h xml_xpath_context.h		\
  xml_element_content.h xml_sax_parser_context.h xml_sax_parser.h	\
  xml_sax_push_parser.h xml_reader.h html_sax_parser_context.h		\
  xslt_stylesheet.h xml_syntax_error.h xml_schema.h xml_relax_ng.h	\
  html_element_description.h xml_namespace.h xml_encoding_handler.h

xml_entity_reference.o: xml_entity_reference.c xml_entity_reference.h	\
  nokogiri.h xml_io.h xml_document.h html_entity_lookup.h		\
  html_document.h xml_node.h xml_text.h xml_cdata.h xml_attr.h		\
  xml_processing_instruction.h xml_document_fragment.h xml_comment.h	\
  xml_node_set.h xml_dtd.h xml_attribute_decl.h xml_element_decl.h	\
  xml_entity_decl.h xml_xpath_context.h xml_element_content.h		\
  xml_sax_parser_context.h xml_sax_parser.h xml_sax_push_parser.h	\
  xml_reader.h html_sax_parser_context.h xslt_stylesheet.h		\
  xml_syntax_error.h xml_schema.h xml_relax_ng.h			\
  html_element_description.h xml_namespace.h xml_encoding_handler.h

xml_io.o: xml_io.c xml_io.h nokogiri.h xml_document.h			\
  html_entity_lookup.h html_document.h xml_node.h xml_text.h		\
  xml_cdata.h xml_attr.h xml_processing_instruction.h			\
  xml_entity_reference.h xml_document_fragment.h xml_comment.h		\
  xml_node_set.h xml_dtd.h xml_attribute_decl.h xml_element_decl.h	\
  xml_entity_decl.h xml_xpath_context.h xml_element_content.h		\
  xml_sax_parser_context.h xml_sax_parser.h xml_sax_push_parser.h	\
  xml_reader.h html_sax_parser_context.h xslt_stylesheet.h		\
  xml_syntax_error.h xml_schema.h xml_relax_ng.h			\
  html_element_description.h xml_namespace.h xml_encoding_handler.h

xml_namespace.o: xml_namespace.c xml_namespace.h nokogiri.h xml_io.h	\
  xml_document.h html_entity_lookup.h html_document.h xml_node.h	\
  xml_text.h xml_cdata.h xml_attr.h xml_processing_instruction.h	\
  xml_entity_reference.h xml_document_fragment.h xml_comment.h		\
  xml_node_set.h xml_dtd.h xml_attribute_decl.h xml_element_decl.h	\
  xml_entity_decl.h xml_xpath_context.h xml_element_content.h		\
  xml_sax_parser_context.h xml_sax_parser.h xml_sax_push_parser.h	\
  xml_reader.h html_sax_parser_context.h xslt_stylesheet.h		\
  xml_syntax_error.h xml_schema.h xml_relax_ng.h			\
  html_element_description.h xml_encoding_handler.h

xml_node.o: xml_node.c xml_node.h nokogiri.h xml_io.h xml_document.h	\
  html_entity_lookup.h html_document.h xml_text.h xml_cdata.h		\
  xml_attr.h xml_processing_instruction.h xml_entity_reference.h	\
  xml_document_fragment.h xml_comment.h xml_node_set.h xml_dtd.h	\
  xml_attribute_decl.h xml_element_decl.h xml_entity_decl.h		\
  xml_xpath_context.h xml_element_content.h xml_sax_parser_context.h	\
  xml_sax_parser.h xml_sax_push_parser.h xml_reader.h			\
  html_sax_parser_context.h xslt_stylesheet.h xml_syntax_error.h	\
  xml_schema.h xml_relax_ng.h html_element_description.h		\
  xml_namespace.h xml_encoding_handler.h

xml_node_set.o: xml_node_set.c xml_node_set.h nokogiri.h xml_io.h	\
  xml_document.h html_entity_lookup.h html_document.h xml_node.h	\
  xml_text.h xml_cdata.h xml_attr.h xml_processing_instruction.h	\
  xml_entity_reference.h xml_document_fragment.h xml_comment.h		\
  xml_dtd.h xml_attribute_decl.h xml_element_decl.h xml_entity_decl.h	\
  xml_xpath_context.h xml_element_content.h xml_sax_parser_context.h	\
  xml_sax_parser.h xml_sax_push_parser.h xml_reader.h			\
  html_sax_parser_context.h xslt_stylesheet.h xml_syntax_error.h	\
  xml_schema.h xml_relax_ng.h html_element_description.h		\
  xml_namespace.h xml_encoding_handler.h

xml_processing_instruction.o: xml_processing_instruction.c		\
 xml_processing_instruction.h nokogiri.h xml_io.h xml_document.h	\
 html_entity_lookup.h html_document.h xml_node.h xml_text.h		\
 xml_cdata.h xml_attr.h xml_entity_reference.h xml_document_fragment.h	\
 xml_comment.h xml_node_set.h xml_dtd.h xml_attribute_decl.h		\
 xml_element_decl.h xml_entity_decl.h xml_xpath_context.h		\
 xml_element_content.h xml_sax_parser_context.h xml_sax_parser.h	\
 xml_sax_push_parser.h xml_reader.h html_sax_parser_context.h		\
 xslt_stylesheet.h xml_syntax_error.h xml_schema.h xml_relax_ng.h	\
 html_element_description.h xml_namespace.h xml_encoding_handler.h

xml_reader.o: xml_reader.c xml_reader.h nokogiri.h xml_io.h		\
  xml_document.h html_entity_lookup.h html_document.h xml_node.h	\
  xml_text.h xml_cdata.h xml_attr.h xml_processing_instruction.h	\
  xml_entity_reference.h xml_document_fragment.h xml_comment.h		\
  xml_node_set.h xml_dtd.h xml_attribute_decl.h xml_element_decl.h	\
  xml_entity_decl.h xml_xpath_context.h xml_element_content.h		\
  xml_sax_parser_context.h xml_sax_parser.h xml_sax_push_parser.h	\
  html_sax_parser_context.h xslt_stylesheet.h xml_syntax_error.h	\
  xml_schema.h xml_relax_ng.h html_element_description.h		\
  xml_namespace.h xml_encoding_handler.h

xml_relax_ng.o: xml_relax_ng.c xml_relax_ng.h nokogiri.h xml_io.h	\
  xml_document.h html_entity_lookup.h html_document.h xml_node.h	\
  xml_text.h xml_cdata.h xml_attr.h xml_processing_instruction.h	\
  xml_entity_reference.h xml_document_fragment.h xml_comment.h		\
  xml_node_set.h xml_dtd.h xml_attribute_decl.h xml_element_decl.h	\
  xml_entity_decl.h xml_xpath_context.h xml_element_content.h		\
  xml_sax_parser_context.h xml_sax_parser.h xml_sax_push_parser.h	\
  xml_reader.h html_sax_parser_context.h xslt_stylesheet.h		\
  xml_syntax_error.h xml_schema.h html_element_description.h		\
  xml_namespace.h xml_encoding_handler.h

xml_sax_parser.o: xml_sax_parser.c xml_sax_parser.h nokogiri.h		\
  xml_io.h xml_document.h html_entity_lookup.h html_document.h		\
  xml_node.h xml_text.h xml_cdata.h xml_attr.h				\
  xml_processing_instruction.h xml_entity_reference.h			\
  xml_document_fragment.h xml_comment.h xml_node_set.h xml_dtd.h	\
  xml_attribute_decl.h xml_element_decl.h xml_entity_decl.h		\
  xml_xpath_context.h xml_element_content.h xml_sax_parser_context.h	\
  xml_sax_push_parser.h xml_reader.h html_sax_parser_context.h		\
  xslt_stylesheet.h xml_syntax_error.h xml_schema.h xml_relax_ng.h	\
  html_element_description.h xml_namespace.h xml_encoding_handler.h

xml_sax_parser_context.o: xml_sax_parser_context.c			\
 xml_sax_parser_context.h nokogiri.h xml_io.h xml_document.h		\
 html_entity_lookup.h html_document.h xml_node.h xml_text.h		\
 xml_cdata.h xml_attr.h xml_processing_instruction.h			\
 xml_entity_reference.h xml_document_fragment.h xml_comment.h		\
 xml_node_set.h xml_dtd.h xml_attribute_decl.h xml_element_decl.h	\
 xml_entity_decl.h xml_xpath_context.h xml_element_content.h		\
 xml_sax_parser.h xml_sax_push_parser.h xml_reader.h			\
 html_sax_parser_context.h xslt_stylesheet.h xml_syntax_error.h		\
 xml_schema.h xml_relax_ng.h html_element_description.h			\
 xml_namespace.h xml_encoding_handler.h

xml_sax_push_parser.o: xml_sax_push_parser.c xml_sax_push_parser.h	\
  nokogiri.h xml_io.h xml_document.h html_entity_lookup.h		\
  html_document.h xml_node.h xml_text.h xml_cdata.h xml_attr.h		\
  xml_processing_instruction.h xml_entity_reference.h			\
  xml_document_fragment.h xml_comment.h xml_node_set.h xml_dtd.h	\
  xml_attribute_decl.h xml_element_decl.h xml_entity_decl.h		\
  xml_xpath_context.h xml_element_content.h xml_sax_parser_context.h	\
  xml_sax_parser.h xml_reader.h html_sax_parser_context.h		\
  xslt_stylesheet.h xml_syntax_error.h xml_schema.h xml_relax_ng.h	\
  html_element_description.h xml_namespace.h xml_encoding_handler.h

xml_schema.o: xml_schema.c xml_schema.h nokogiri.h xml_io.h		\
  xml_document.h html_entity_lookup.h html_document.h xml_node.h	\
  xml_text.h xml_cdata.h xml_attr.h xml_processing_instruction.h	\
  xml_entity_reference.h xml_document_fragment.h xml_comment.h		\
  xml_node_set.h xml_dtd.h xml_attribute_decl.h xml_element_decl.h	\
  xml_entity_decl.h xml_xpath_context.h xml_element_content.h		\
  xml_sax_parser_context.h xml_sax_parser.h xml_sax_push_parser.h	\
  xml_reader.h html_sax_parser_context.h xslt_stylesheet.h		\
  xml_syntax_error.h xml_relax_ng.h html_element_description.h		\
  xml_namespace.h xml_encoding_handler.h

xml_syntax_error.o: xml_syntax_error.c xml_syntax_error.h nokogiri.h	\
  xml_io.h xml_document.h html_entity_lookup.h html_document.h		\
  xml_node.h xml_text.h xml_cdata.h xml_attr.h				\
  xml_processing_instruction.h xml_entity_reference.h			\
  xml_document_fragment.h xml_comment.h xml_node_set.h xml_dtd.h	\
  xml_attribute_decl.h xml_element_decl.h xml_entity_decl.h		\
  xml_xpath_context.h xml_element_content.h xml_sax_parser_context.h	\
  xml_sax_parser.h xml_sax_push_parser.h xml_reader.h			\
  html_sax_parser_context.h xslt_stylesheet.h xml_schema.h		\
  xml_relax_ng.h html_element_description.h xml_namespace.h		\
  xml_encoding_handler.h

xml_text.o: xml_text.c xml_text.h nokogiri.h xml_io.h xml_document.h	\
  html_entity_lookup.h html_document.h xml_node.h xml_cdata.h		\
  xml_attr.h xml_processing_instruction.h xml_entity_reference.h	\
  xml_document_fragment.h xml_comment.h xml_node_set.h xml_dtd.h	\
  xml_attribute_decl.h xml_element_decl.h xml_entity_decl.h		\
  xml_xpath_context.h xml_element_content.h xml_sax_parser_context.h	\
  xml_sax_parser.h xml_sax_push_parser.h xml_reader.h			\
  html_sax_parser_context.h xslt_stylesheet.h xml_syntax_error.h	\
  xml_schema.h xml_relax_ng.h html_element_description.h		\
  xml_namespace.h xml_encoding_handler.h

xml_xpath_context.o: xml_xpath_context.c xml_xpath_context.h		\
  nokogiri.h xml_io.h xml_document.h html_entity_lookup.h		\
  html_document.h xml_node.h xml_text.h xml_cdata.h xml_attr.h		\
  xml_processing_instruction.h xml_entity_reference.h			\
  xml_document_fragment.h xml_comment.h xml_node_set.h xml_dtd.h	\
  xml_attribute_decl.h xml_element_decl.h xml_entity_decl.h		\
  xml_element_content.h xml_sax_parser_context.h xml_sax_parser.h	\
  xml_sax_push_parser.h xml_reader.h html_sax_parser_context.h		\
  xslt_stylesheet.h xml_syntax_error.h xml_schema.h xml_relax_ng.h	\
  html_element_description.h xml_namespace.h xml_encoding_handler.h

xslt_stylesheet.o: xslt_stylesheet.c xslt_stylesheet.h nokogiri.h	\
  xml_io.h xml_document.h html_entity_lookup.h html_document.h		\
  xml_node.h xml_text.h xml_cdata.h xml_attr.h				\
  xml_processing_instruction.h xml_entity_reference.h			\
  xml_document_fragment.h xml_comment.h xml_node_set.h xml_dtd.h	\
  xml_attribute_decl.h xml_element_decl.h xml_entity_decl.h		\
  xml_xpath_context.h xml_element_content.h xml_sax_parser_context.h	\
  xml_sax_parser.h xml_sax_push_parser.h xml_reader.h			\
  html_sax_parser_context.h xml_syntax_error.h xml_schema.h		\
  xml_relax_ng.h html_element_description.h xml_namespace.h		\
  xml_encoding_handler.h
all: clean-ports

clean-ports: $(DLLIB)
	-$(Q)$(RUBY) $(srcdir)/extconf.rb --clean --enable-static
