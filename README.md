# QT-Tcp-connection-project
this is a QT project that connection server and client by tcp/ip.

## platform： win10  QT5.8 + msvc2013
这是一个简单的利用tcp来进行连接的程序，其中MyTcpServer是服务器端的程序，MyTcpClient是客户端的程序，两者可以在局域网下或者网线连接的情况下进行通讯。

还未深入了解心跳机制等更深层次的网络连接内容。

后续可以做成通过一个软件通过网络连接发送参数（参数可以当做标志位）进而控制另一个软件的运行，或者类似参数下载的功能。

![server picture](https://github.com/herrkun/QT-Tcp-connection-project/blob/master/server.png)  

![server picture](https://github.com/herrkun/QT-Tcp-connection-project/blob/master/client.png)
