#
# To regenerate all thes files use :
#    $ autoreconf --install
#

AC_INIT([sioclient], [1.6.0])
AM_INIT_AUTOMAKE([-Wall -Werror foreign subdir-objects])
AC_CONFIG_MACRO_DIRS([m4])
AM_PROG_AR
LT_INIT

AC_CONFIG_FILES([Makefile])

AC_PROG_CXX
AX_CXX_COMPILE_STDCXX(11)

AX_BOOST_BASE([1.55.0], [], [AC_MSG_ERROR("boost library not found (system date_time random are required)")])
# REQUIRED system date_time random

AC_OUTPUT

