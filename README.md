annotated-redis-2.8.2
=====================
关于Redis-2.8.2源码注释的说明
==============================
本项目是Redis-2.8.2源码的注释，源码来自： https://github.com/antirez/redis 

已经注释的代码包括：
1、底层数据结构；链表、字典、简单动态字符串、压缩列表、跳跃表、整合集合
2、SET, LIST, HASH TABLE, STRING, ZSET指令的实现代码
3、Redis的事件循环
4、AOF
5、Redis网络通讯

未注释的代码包括；
1、SENTINEL 
2、REPLICATION
3、RDB
4、一些辅助模块

此份Redis源码注释参考了许多网上大牛的博客，以及huangz的对于2.6源码的注释，对此表示感谢。
同时添加了许多我个人对源码的理解，注释部分写的比较随意，可能有注释不妥之处。

本人的博客也在同步更新Redis的相关博客，您可以在此了解到更多更详细的关于Redis源码的解析；
http://blog.csdn.net/acceptedxukai/article/category/1805009
同时欢迎在博客中与我讨论。

Enjoy！

xkey
2014.01.10 于武汉