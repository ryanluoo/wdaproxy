# wdaproxy
==========

基于[wdaproxy](https://github.com/openatx/wdaproxy)扩展，基础能力请参考原项目

## Add: 通过-f指定WDA端口
命令使用：
```
wdaproxy -f 7100 -p 4002
```
输出：
```
2019/05/31 11:36:37 main.go:133: freeport 55764
2019/05/31 11:36:37 main.go:216: Open webbrower with http://10.95.52.188:4002
2019/05/31 11:36:37 main.go:136: launch tcp-proxy, listen on 4002
2019/05/31 11:36:37 main.go:143: launch iproxy (udid: "0d1860684c3467c3afac5ade7f98cb26852358bf") from (forwarded port: 7100)
[11:36:58] 200 GET /remote (::1) 1.63ms
[11:36:58] 200 GET /favicon.ico (::1) 10.76ms
[11:36:59] 200 GET /status (::1) 814.17ms
[11:36:59] 200 GET /session/4D26C15B-E0E3-4ECB-B14A-EBB4CFF4B95F/window/size (::1) 392.84ms
[11:36:59] 200 GET /screenshot (::1) 1272.55ms
[11:36:59] 200 GET /status (::1) 3.38ms
[11:37:00] 200 GET /session/4D26C15B-E0E3-4ECB-B14A-EBB4CFF4B95F/window/size (::1) 372.30ms
[11:37:01] 200 GET /screenshot (::1) 873.27ms
[11:37:02] 200 GET /screenshot (::1) 803.45ms
```
