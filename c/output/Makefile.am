noinst_LTLIBRARIES=	liboutput.la
liboutput_la_SOURCES=	\
			file_output_mode.h \
			lrec_writer.h \
			lrec_writer_csv.c \
			lrec_writer_csvlite.c \
			lrec_writer_dkvp.c \
			lrec_writer_json.c \
			lrec_writer_markdown.c \
			lrec_writer_nidx.c \
			lrec_writer_pprint.c \
			lrec_writer_xtab.c \
			lrec_writers.c \
			lrec_writers.h \
			multi_lrec_writer.c \
			multi_lrec_writer.h \
			multi_out.c \
			multi_out.h
liboutput_la_LIBADD=	\
                        ../lib/libmlr.la \
                        ../containers/libcontainers.la
liboutput_la_CPPFLAGS=	-I${srcdir}/../
liboutput_la_CFLAGS=	-std=gnu99
