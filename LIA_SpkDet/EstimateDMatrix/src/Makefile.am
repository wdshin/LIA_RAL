bin_PROGRAMS=EstimateDMatrix
EstimateDMatrix_SOURCES= \
	EstimateDMatrix.cpp\
	EstimateDMatrixMain.cpp

EstimateDMatrix_CPPFLAGS=-I../include -I$(top_srcdir)/LIA_SpkTools/include -I$(ALIZE_PATH)/include
EstimateDMatrix_LDFLAGS=-L$(top_srcdir)/lib -L$(ALIZE_PATH)/lib
EstimateDMatrix_LDADD=-lliatools_${OS}_${ARCH}${DEBUG} $(lib_alize) $(LIBTHREAD)

all:
	mv ${bin_PROGRAMS} ${top_srcdir}/bin
