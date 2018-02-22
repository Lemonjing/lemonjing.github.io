---
layout: post
title: 【Scala】Scala与Java混合编程最佳实践
tags: Spark
category: 大数据
---

## 混合编程的最佳实践

1、打包编译 mvn clean scala:compile compile -DskipTests -Ponline 让scala优先编译

2、import scala.collection.JavaConverters._ 以使用asScala和asJava

建议使用 

```
import scala.collection.JavaConverters._ 显示转换而不是
import scala.collection.JavaConversions._ （旧版本）
```

3、Scala Map(immutable) 与 mutable Map

immutable使用var的+=, mutable使用val的put或者+=

> 持续更新

ps：公众号已正式接入图灵机器人，快去和我聊聊吧。

<center>-END-</center>

<div align="center">
<img src="http://7xlkoc.com1.z0.glb.clouddn.com/qrcodenew.jpg" width="400" height="320" />
</div>

> 本文系本人个人公众号「梦回少年」原创发布，扫一扫加关注。