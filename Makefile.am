ACLOCAL_AMFLAGS = -I config
AM_CXXFLAGS = -g -Wall -Wstrict-aliasing=0 -Werror -Isrc

bin_PROGRAMS = out

out_SOURCES = src/main.cc src/common.cc
out_SOURCES += src/general/loopback.cc

if PEER_DIRECT
out_SOURCES += src/peerdirect/loopback.cc
endif

EXTRA_DIST = autogen.sh
