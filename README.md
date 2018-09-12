# POC-T: *Pentest Over Concurrent Toolkit* 

## Referer
[http://www.freebuf.com/sectool/176562.html](http://www.freebuf.com/sectool/176562.html)

## 使用
- `poc-t.py --batch -iF 1.txt` 使用fuzz脚本
- `poc-t.py -eT -t 20 -s xx -iF 1w.txt`

## 插件
- waf 检测waf 并返回没有waf的url
- craw 爬取链接中的相关地址
- vulscan 检测sql注入漏洞
- portscan 端口扫描，检测弱口令服务
- findsub 查找子域名
