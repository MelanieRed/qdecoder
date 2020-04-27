################################################################################
## qDecoder - http://www.qdecoder.org
##
## Copyright (c) 2000-2012 Seungyoung Kim.
## All rights reserved.
##
## Redistribution and use in source and binary forms, with or without
## modification, are permitted provided that the following conditions are met:
##
## 1. Redistributions of source code must retain the above copyright notice,
##    this list of conditions and the following disclaimer.
## 2. Redistributions in binary form must reproduce the above copyright notice,
##    this list of conditions and the following disclaimer in the documentation
##    and/or other materials provided with the distribution.
##
## THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
## AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
## IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
## ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE
## LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
## CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
## SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
## INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
## CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
## ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
## POSSIBILITY OF SUCH DAMAGE.
################################################################################
## $Id: Makefile.in 636 2012-05-07 23:40:43Z seungyoung.kim $
################################################################################

if EXAMPLES_ENABLED
bin_PROGRAMS = cookie.cgi download.cgi multivalue.cgi query.cgi session.cgi upload.cgi uploadfile.cgi

AM_CPPFLAGS = -I$(top_srcdir)/src

cookie_cgi_SOURCES = cookie.c
cookie_cgi_LDADD = ../src/libqdecoder.la

download_cgi_SOURCES = download.c
download_cgi_LDADD = ../src/libqdecoder.la

multivalue_cgi_SOURCES = multivalue.c
multivalue_cgi_LDADD = ../src/libqdecoder.la

query_cgi_SOURCES = query.c
query_cgi_LDADD = ../src/libqdecoder.la

session_cgi_SOURCES = session.c
session_cgi_LDADD = ../src/libqdecoder.la

upload_cgi_SOURCES = upload.c
upload_cgi_LDADD = ../src/libqdecoder.la

uploadfile_cgi_SOURCES = uploadfile.c
uploadfile_cgi_LDADD = ../src/libqdecoder.la
endif
