## CSDN博客刷流量的小脚本
- 前段时间写了人生第一篇博客，但发现看的人很少，所以有了换ip 刷访问量的想法，结合自己以前随手写的ip 小脚本，做个demo 

- 使用方法，找到 demo.py 修改里面的博客地址即可，运行即可。


## 2018/6/16 更新
- 目前就需求来讲，ip量不需要很大，暂时只使用 66.ip.com , 今天发现该网址不可用，在 headers 增加 Host 字段即可

## 2018/6/21
- 访问博客的过程，增加了多线程
- 打算IP抓取的过程中，也使用多线程，日后再改