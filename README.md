gost script
======
### 一个可以将你从v2ray或shadowsocks相关软件复制来的链接转成 gost 或者 glider 命令的脚本

#### 如何在Telegram上使用
------
* telegram 机器人用户名 @gostscriptbot . 
* telegram 机器人用户名 @gliderscriptbot . 

#### How to use on windows tor.
------
* 1 download tor browser ( https://www.torproject.org/download/ ) , proxychains for windows ( https://github.com/shunf4/proxychains-windows ) , curl for windows ( https://curl.se/windows/ ).
* 2 follow proxychains User guide ,edit socks5 port to 9150 in conf file (Do it yourself)
* 3 Use following command to start .
change content to gost command.
``` 
proxychains -f proxychains.conf curl http://e7218dgyy89xdsa8yqe332.onion/gost?content={your content}
```
change content to glider command.
``` 
proxychains -f proxychains.conf curl http://e7218dgyy89xdsa8yqe332.onion/glider?content={your content}
```

#### How to use on linux tor.
------
It's about the same as windows
