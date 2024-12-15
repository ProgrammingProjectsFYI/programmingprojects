---
title: "Build Your Own Echo Server"
description: "This project is to build an Echo server."
tags: [server, networking, protocol, tcp, udp]
categories: [network server]
ShowToc: true
TocOpen: true
---

Build your own Echo server. Implement a UDP or TCP based Echo server that echoes back to the client whatever is sent to it..

<!--more-->

An Echo server listens for connections from clients then echoes back to the client whatever the client sent to the server.

The echo protocol is formally defined in RFC862. It's probably the shortest protocol description ever! Here it is:

TCP Based Echo Service

   One echo service is defined as a connection based application on TCP.
   A server listens for TCP connections on TCP port 7.  Once a
   connection is established any data received is sent back.  This
   continues until the calling user terminates the connection.

UDP Based Echo Service

   Another echo service is defined as a datagram based application on
   UDP.  A server listens for UDP datagrams on UDP port 7.  When a
   datagram is received, the data from it is sent back in an answering
   datagram.