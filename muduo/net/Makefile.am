MAINTAINERCLEANFILES = Makefile.in

INCLUDES        = -I$(top_builddir) -I$(top_builddir)/muduo/net \
                -I$(top_srcdir) -I$(top_srcdir)/muduo/net

lib_LIBRARIES   = libmuduo_net.a
libmuduo_net_a_SOURCES = Acceptor.cc Buffer.cc Channel.cc Connector.cc EventLoop.cc EventLoopThread.cc EventLoopThreadPool.cc InetAddress.cc Poller.cc poller/DefaultPoller.cc poller/EPollPoller.cc poller/PollPoller.cc Socket.cc SocketsOps.cc TcpClient.cc TcpConnection.cc TcpServer.cc Timer.cc TimerQueue.cc
