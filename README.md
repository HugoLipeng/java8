# java8

link with https://github.com/HugoLipeng/java8_demo


### 第一级别：精读源码

该级别包含的包如下：

```
java.io
java.lang
java.util
```

其实上面三个包都有一个共同点，那就是这三个包，基本上都是你最常用的了。lang包不用说了，你随便写点啥都得用到，io包和util包也是你平时读写文件和使用数据结构必不可少的。

### 第二级别：深刻理解

该级别包含的包如下：

```
java.lang.reflect
java.net
javax.net.*
java.nio.*
java.util.concurrent.*
```

reflect代表了反射，net代表了网络IO，nio代表了非阻塞io，concurrent代表了并发。  
举个例子，反射你要了解清楚的话，你是不是要搞明白JVM的类加载机制？网络IO要搞清楚的话，你是不是要清楚TCP/IP和HTTP、HTTPS？包括并发包，如果你要搞清楚的话，是不是要了解并发的相关知识？因此，这四个包要彻底搞清楚，还是需要花费一定时间和精力的。但是，请相信我，这绝对是值得的，甚至可以说，这四个包用的够不够溜，基本决定了一个Java程序员所处的档次。

### 第三级别：会用即可
该级别包含的包如下：

```
java.lang.annotation  
javax.annotation.*
java.lang.ref
java.math
java.rmi.*
javax.rmi.*
java.security.*
javax.security.*
java.sql
javax.sql.*
javax.transaction.*
java.text
javax.xml.*
org.w3c.dom.*
org.xml.sax.*
javax.crypto.*
javax.imageio.*
javax.jws.*
java.util.jar
java.util.logging
java.util.prefs
java.util.regex
java.util.zip
```

