bin_PROGRAMS = cec-audio
man_MANS = cec-audio.1

cec_audio_SOURCES = cec-audio.cpp cec-audio.h cec-processing.cpp cec-tuner.cpp
cec_audio_CPPFLAGS = -I$(top_srcdir)/utils/libcecutil $(GIT_SHA) $(GIT_COMMIT_CNT) $(GIT_COMMIT_DATE)
cec_audio_LDADD = -lrt ../libcecutil/libcecutil.la

EXTRA_DIST = cec-audio.1
