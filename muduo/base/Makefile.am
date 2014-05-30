MAINTAINERCLEANFILES = Makefile.in

INCLUDES        = -I$(top_builddir) -I$(top_builddir)/muduo/base \
                -I$(top_srcdir) -I$(top_srcdir)/muduo/base

lib_LIBRARIES   = libmuduo_base.a
libmuduo_base_a_SOURCES = AsyncLogging.cc Condition.cc CountDownLatch.cc Date.cc Exception.cc FileUtil.cc LogFile.cc Logging.cc LogStream.cc ProcessInfo.cc Timestamp.cc TimeZone.cc Thread.cc ThreadPool.cc
LIBS            = -lpthread -lrt
