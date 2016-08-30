---
layout: post
title: "字节的掌握"
author: "sher"
date: 2016-08-23 23:07
tags:
    - byte code
---

计算机存储的最小单元为位，又叫bit。 计量单位是byte，8位bit又是1byte。1Byte＝8bit，1KB=1024B，1MB=1024KB，1GB=1024MB，1TB=1024GB。

### Q1 byte 位运算

```
 byte ba=127;
 byte bb=ba<<2;
 System.out.println(bb);
 这个为什么会出错？给出解释，并且纠正错误
```

Java语言中，基本类型的数据都是有符号数据，取值范围：

byte (-128~+127)
