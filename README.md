gost script
======
### 一个可以将你从v2ray或shadowsocks相关软件复制来的链接转成 gost 或者 glider 命令的脚本

#### 联系方式
------
* Telegram频道: @gogostsc @gliderscript 
* 邮箱: sharewithyousome@protonmail.com

#### 如何在Telegram上使用
------
* telegram 机器人用户名 @gostscriptbot , 打开它会有教程教你. 
* telegram 机器人用户名 @gliderscriptbot ,打开它会有教程教你. 

#### 如何在windows上使用
------
* 1 下载洋葱浏览器 ( https://www.torproject.org/download/ ) , proxychains windows 版本 ( https://github.com/shunf4/proxychains-windows ) , curl windows 版本 ( https://curl.se/windows/ ).
* 2 阅读proxychains操作指南 ,修改配置文件中的 socks5 端口到 9150 (自行解决)
* 3 使用下面的命令开始你的使用吧

订阅链接转gost脚本
``` 
proxychains -f proxychains.conf curl http://e7218dgyy89xdsa8yqe332.onion/gost?content={your content}
```
订阅链接转glider脚本
``` 
proxychains -f proxychains.conf curl http://e7218dgyy89xdsa8yqe332.onion/glider?content={your content}
```

#### 如何在linux使用.
------
和windows差不多

#### 免责声明
------
阅读该目录下Disclaimer和Disclaimer_en文件
