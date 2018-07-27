# multiudp_server_app

以UDP组播方式进行局域网发现。

当网络拓扑结构为电脑端直连ESP8266模块（AP方式），ESP8266可以接收到电脑端发送出来的组播消息（239.1.1.1）

当网络拓扑结构为：电脑端和ESP8266去连接路由器，电脑端发送的组播，ESP8266接收不到数据。

不成功的原因可能是路由器禁止了组播协议。

可以使用tools文件夹里的Python脚本进行组播发送数据测试.


