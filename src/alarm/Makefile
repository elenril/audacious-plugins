PLUGIN = alarm${PLUGIN_SUFFIX}

SRCS = alarm.c		\
       interface.c

include ../../buildsys.mk
include ../../extra.mk

plugindir := ${plugindir}/${GENERAL_PLUGIN_DIR}

CFLAGS += ${PLUGIN_CFLAGS}
CPPFLAGS += ${PLUGIN_CPPFLAGS} ${GTK_CFLAGS} ${GLIB_CFLAGS} -I../..
LIBS += ${GTK_LIBS} ${GLIB_LIBS}
