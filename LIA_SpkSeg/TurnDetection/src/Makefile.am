bin_PROGRAMS=TurnDetection
TurnDetection_SOURCES= \
	TurnDetection.cpp\
	TurnDetectionMain.cpp

TurnDetection_CPPFLAGS=-I../include -I$(top_srcdir)/LIA_SpkTools/include -I$(ALIZE_PATH)/include
TurnDetection_LDFLAGS=-L$(top_srcdir)/lib -L$(ALIZE_PATH)/lib
TurnDetection_LDADD=-lliatools_${OS}_${ARCH}${DEBUG} $(lib_alize) $(LIBTHREAD)

all:
	mv ${bin_PROGRAMS} ${top_srcdir}/bin
