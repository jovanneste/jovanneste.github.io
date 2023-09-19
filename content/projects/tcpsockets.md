+++
showonlyimage = false
draft = false
image = "projects/sock.jpg"
date = "2021-05-28T10:16:56+01:00"
title = "TCP network connection using Python sockets"
weight = 7
+++

Built a solution that empowers developers to establish, manage, and communicate over TCP/IP networks effortlessly using Python's socket library[^1]. 
<!--more-->

---

#### Description 
Create a Python [Socket](https://docs.python.org/3/library/socket.html) for end-to-end communication and file transfer. One side acts as the server - starting the communction with a port number. The other side acts as the client - connecting to this port number. With every transfer over network connections, checksums are calculated to enuse no data has been lost. 

> [View code on GitHub](https://github.com/jovanneste/pythonSocketTCP)

[^1]: Provides a set of modules that enable you to create, manipulate, and work with sockets for network communication.