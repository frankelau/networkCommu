一、传统阻塞式IO通信
1).server端:创建一个server = new ServerSocket(PROT);
2).server端:server.accept()阻塞接收客户端的信息
3).client端:创建一个client = new Socket(ADDRESS, PORT);
4).client端:client发送数据,client.readLine()阻塞接收服务端的响应
5).server端:接收到数据后，响应数据
6).client端:client接收响应数据
7).关资源，结束