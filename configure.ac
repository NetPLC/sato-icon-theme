AC_PREREQ(2.53)

AC_INIT([sato-icon-theme], [0.3.2],
        [http://www.openedhand.com/])
AC_CONFIG_SRCDIR([16x16])

AM_INIT_AUTOMAKE([1.9 tar-ustar])

# Define the toplevel path here
AC_SUBST(themedir, "\${datadir}/icons/Sato")

UTILS_REQUIRED=0.8.2

AC_MSG_CHECKING([icon-naming-utils >= $UTILS_REQUIRED])
PKG_CHECK_EXISTS(icon-naming-utils >= $UTILS_REQUIRED,
                 have_utils=yes, have_utils=no)
if test "x$have_utils" = "xyes"; then
   UTILS_PATH="`$PKG_CONFIG --variable=program_path icon-naming-utils`"
   ICONMAP="$UTILS_PATH/icon-name-mapping"
   AC_SUBST(ICONMAP)
   AC_MSG_RESULT([yes])
else
   AC_MSG_RESULT([no])
   AC_MSG_ERROR([icon-naming-utils >= $UTILS_REQUIRED is required to build
                 and install sato-icon-theme])
fi


AC_CONFIG_FILES([
Makefile
16x16/actions/Makefile
16x16/apps/Makefile
16x16/devices/Makefile
16x16/Makefile
16x16/mimetypes/Makefile
16x16/places/Makefile
16x16/status/Makefile
16x16/stock/Makefile
22x22/actions/Makefile
22x22/apps/Makefile
22x22/devices/Makefile
22x22/Makefile
22x22/mimetypes/Makefile
22x22/places/Makefile
22x22/status/Makefile
22x22/stock/Makefile
32x32/actions/Makefile
32x32/apps/Makefile
32x32/devices/Makefile
32x32/Makefile
32x32/mimetypes/Makefile
32x32/places/Makefile
32x32/status/Makefile
32x32/stock/Makefile
48x48/actions/Makefile
48x48/apps/Makefile
48x48/devices/Makefile
48x48/Makefile
48x48/mimetypes/Makefile
48x48/places/Makefile
48x48/status/Makefile
48x48/stock/Makefile
64x64/actions/Makefile
64x64/apps/Makefile
64x64/devices/Makefile
64x64/Makefile
64x64/mimetypes/Makefile
64x64/places/Makefile
64x64/status/Makefile
64x64/stock/Makefile
])

AC_OUTPUT
