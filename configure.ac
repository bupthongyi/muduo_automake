# @start 1
# configure.in -- Process this file with autoconf to produce configure
# @end 1
# Copyright (C) 2000, 2006 Gary V. Vaughan
#
# This program is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 2, or (at your option)
# any later version.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program; if not, write to the Free Software
# Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston,
# MA 02110-1301, USA.

# @start 2

AC_PREREQ([2.59])

AC_INIT([muduo], [0.1.0], [lihongyi@gmail.com])
AC_CONFIG_HEADERS([config.h])

AM_INIT_AUTOMAKE([1.9 foreign])

AC_PROG_CC
AC_PROG_CXX
AC_PROG_RANLIB

AC_HEADER_STDC
AC_HEADER_SYS_WAIT
AC_CHECK_HEADERS([errno.h stddef.h stdlib.h string.h strings.h unistd.h])

AC_CONFIG_FILES([Makefile muduo/base/Makefile muduo/net/Makefile examples/netty/discard/Makefile])

AC_OUTPUT
# @end 2
