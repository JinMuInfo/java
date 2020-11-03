1.网络模型与协议

OSI 七层模式 : 应用层，表示层，会话层，传输层，网络层，链路层，物理层

 

五层模型: 应用层, 传输层，网络层，链路层，物理层
四层模型 ： 应用层, 传输层，网络层，链路层

应用层：http（超文本传输协议） ftp(文件传输协议) stmp (邮件发送协议) pop3（邮件接收协议）, ssh ( 安全shell，用于远程登录）

传输层: tcp(安全可靠的协议) udp(不可靠)

网络层：ip

windows下可以使用 ipconfig来查看ip地址
linux 下可以使用 ifconfig来查看ip地址

ip 地址的作用是用来定位到网络上的另一台计算机


port 端口，端口号的作用是用来标记，要访问对方的哪个程序

mysql 3306
oracle 1521
sqlserver 1433
redis 6379
tomcat 8080
apache(http的服务) 80
ftp 21
ssh 22
...

传输层协议：
tcp协议：
TCP 协议的特点是： TCP 协议是一个有连接、可靠的协议。所谓有连接，指的是在进行 TCP通信之前，两个需要通信的主机之间要首先建立一条数据通道，就好像打电话进行交流之前，首先要让电话接通一样。所谓可靠，指的是 TCP 协议能够保证： 1、发送端发送的数据不会丢失； 2、接收端接受的数据包的顺序，会按照发送端发送的包的顺序接受。也就是说， TCP协议能够保证数据能够完整无误的传输。

udp协议：
与 TCP 协议相比， UDP 是一个无连接，不可靠的协议。 即：数据的发送方只负责将数据发送出去，数据的接受方只负责接受数据。发送方和接收方不会相互确认数据的传输是否成功。
相对于 TCP 而言， UDP 有一个优点：效率较高。因此，当我们在对数据传输的正确率
不太关心，但是对传输效率要求较高的情况下，可以采用 UDP 协议。典型的使用 UDP 协议的是网络语音以及视频聊天应用。

