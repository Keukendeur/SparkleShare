dist_plugins_in_files = \
    bitbucket.xml.in \
    github.xml.in \
    gitorious.xml.in \
    gnome.xml.in \
    unison.xml.in \
    own-server.xml.in

dist_plugins_DATA = \
    $(dist_plugins_in_files:.xml.in=.xml) \
    github.png \
    gitorious.png \
    bitbucket.png \
    gnome.png \
    unison.png \
    own-server.png

@INTLTOOL_XML_RULE@

pluginsdir = $(pkgdatadir)/plugins/

EXTRA_DIST=$(xml_in_files) $(xml_DATA)

MAINTAINERCLEANFILES = \
	Makefile.in
