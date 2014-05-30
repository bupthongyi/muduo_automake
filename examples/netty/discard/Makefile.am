MAINTAINERCLEANFILES = Makefile.in

INCLUDES        = -I$(top_builddir) \
                -I$(top_srcdir) 

bin_PROGRAMS    = netty_discard_client netty_discard_server
netty_discard_client_SOURCES     = client.cc
netty_discard_client_LDADD       = $(top_builddir)/muduo/net/libmuduo_net.a \
                                  $(top_builddir)/muduo/base/libmuduo_base.a

netty_discard_server_SOURCES     = server.cc
netty_discard_server_LDADD       = $(top_builddir)/muduo/net/libmuduo_net.a \
                                  $(top_builddir)/muduo/base/libmuduo_base.a

LIBS = -lpthread -lrt
