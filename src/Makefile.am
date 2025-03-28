bin_PROGRAMS = myman

myman_SOURCES = \
	myman.c \
	utils.c \
	logic.c

AM_CPPFLAGS = -I$(srcdir)/../inc \
              -DMYMANVARIANT="\"Standard\"" \
              -DMYMANSIZE="\"normal\"" \
              -DMYMANVARIANTS="\"standard alternate\"" \
              -DMYMANSIZES="\"normal small large\""

myman_LDADD = -lncurses
