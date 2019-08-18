dnl Copyright (c) 2019 sidneys.github.io
dnl 
dnl Licensed under the Apache License, Version 2.0 (the "License");
dnl you may not use this file except in compliance with the License.
dnl You may obtain a copy of the License at
dnl 
dnl     http://www.apache.org/licenses/LICENSE-2.0
dnl 
dnl Unless required by applicable law or agreed to in writing, software
dnl distributed under the License is distributed on an "AS IS" BASIS,
dnl WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
dnl See the License for the specific language governing permissions and
dnl limitations under the License.


dnl Autoconf Init
AC_INIT([alac], [1.0.1])
AC_CONFIG_AUX_DIR(.)
AC_CONFIG_MACRO_DIR([m4])
AM_INIT_AUTOMAKE([tar-ustar foreign])
m4_ifdef([AM_SILENT_RULES], [AM_SILENT_RULES([yes])])
AM_MAINTAINER_MODE

dnl Check Compilers
AC_PROG_CC
AC_PROG_CXX

dnl Check Headers
AC_CHECK_HEADERS([stdint.h stdlib.h string.h])

dnl Check Types
AC_CHECK_HEADER_STDBOOL
AC_C_INLINE
AC_TYPE_INT16_T
AC_TYPE_INT32_T
AC_TYPE_INT64_T
AC_TYPE_INT8_T
AC_TYPE_SIZE_T
AC_TYPE_UINT16_T
AC_TYPE_UINT32_T
AC_TYPE_UINT64_T
AC_TYPE_UINT8_T

dnl Libtool Init
LT_INIT

dnl soname version to use
dnl goes by ‘current[:revision[:age]]’ with the soname ending up as
dnl current.age.revision.

dnl Version Variable (soname)
ALAC_VERSION=0
AC_SUBST(ALAC_VERSION)

dnl Configurations List
AC_CONFIG_FILES([Makefile
                 codec/Makefile
                 codec/alac.pc])

dnl Autoconf Finish
AC_OUTPUT
