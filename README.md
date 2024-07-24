# anyproxy

Proxy server supporting http/ssh/socks4/socks5/shadowsocks on port

> 浏览器->端口穿透->局域网代理（http/ssh/socks4/socks5/shadowsocks）->目标服务器

```
git clone -c http.proxy="192.167.1.124:7890" https://github.com/haishanh/yacd.git
```


```
[root@WebSever proxy]# ./anyproxy -a "xieyuhua:xieyuhua@0.0.0.0:1080"
[any proxy] 2024/07/24 11:15:17 listen [
  http://xieyuhua:xieyuhua@0.0.0.0:1080 
  socks4://xieyuhua:xieyuhua@0.0.0.0:1080 
  socks5://xieyuhua:xieyuhua@0.0.0.0:1080 
  ssh://xieyuhua:xieyuhua@0.0.0.0:1080 
  pprof://xieyuhua:xieyuhua@0.0.0.0:1080
]
```



