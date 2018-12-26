shadowsocks-MoreAPI
===========

[![PyPI version]][PyPI]
[![Build Status]][Travis CI]

在 Shadowsocks 3.0 基础上的修改， 增加了一些 API.



新增 API：
-------

### 提供访问记录输出
可以通过在配置文中写入 
"acc_rec_out_cli_port":6666
"acc_rec_out_ser_port":6667
来使得 SS Server 将访问记录通过本地 UDP 发送到 6666 端口。

信息格式： 目标访问网址:目标访问网址端口;客户端IP:客户端端口号;服务器端口号

注意：如果不指定 acc_rec_out_cli_port 则 SS Server 不会输出访问记录，且支持配置文件中指定




