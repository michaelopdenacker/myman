AC_INIT([myman], [0.1], [michael.opdenacker@rootcommit.com])
AM_INIT_AUTOMAKE([foreign subdir-objects])
AC_CONFIG_SRCDIR([src/myman.c])
AC_CONFIG_HEADERS([config.h])

# Checks for programs
AC_PROG_CC

# Checks for header files
AC_CHECK_HEADERS([stdio.h stdlib.h string.h unistd.h])

# Checks for libraries
AC_CHECK_LIB([ncurses], [initscr], [], [AC_MSG_ERROR([ncurses not found])])

# Store prefix option in config.h
AC_DEFINE_UNQUOTED([PREFIX], ["$prefix"], [Installation prefix])

# Output
AC_CONFIG_FILES([Makefile src/Makefile])
AC_OUTPUT
