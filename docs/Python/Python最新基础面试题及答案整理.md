# Python最新基础面试题及答案整理

### 其实，博主还整理了，更多大厂面试题，直接下载吧

### 下载链接：[高清172份，累计 7701 页大厂面试题  PDF](https://github.com/souyunku/DevBooks/blob/master/docs/index.md)



### 1、b、B、kB、MB、GB的关系

**1、** 1B=8b

**2、** 1kB=1024B

**3、** 1MB=1024kB

**4、** 1GB=1024MB


### 2、简述python字符串的驻留机制

[python字符串驻留机制参考文档](https://www.cnblogs.com/asmer-stone/p/4802800.html)

**1、** 相同对象的引用都指向内存中的同一个位置，这个也叫python的字符串驻留机制

**2、** python的引用计数机制，并不是对所有的数字，字符串，他只对”[0-9][a-z][A-Z]

**3、** 和"_"(下划线)  ”有效“，当字符串中由其他字符比如“！ @ # ￥ % -”时字符驻留机制是不起作用的。


### 3、sys.path.append('xxx')的作用

添加搜索路径


### 4、在Python中有多少种运算符？解释一下算数运算符。

在Python中，我们有7种运算符：算术运算符、关系运算符、赋值运算符、逻辑运算符、位运算符、成员运算符、身份运算符。

我们有7个算术运算符，能让我们对数值进行算术运算：

**1、** 加号（+），将两个值相加

```
>>> 7+8
15
```

**2、** 减号（-），将第一个值减去第二个值

```
>>> 7-8
-1
```

**3、** 乘号（*），将两个值相乘

```
>>> 7*8
56
```

**4、** 除号（/），用第二个值除以第一个值

```
>>> 7/8
0.875
>>> 1/1
1.0
```

**5、** 向下取整除、取模和取幂运算，参见上个问题。


### 5、简述OSI七层协议

为了实现计算机系统的互连，OSI参考模型把整个网络的通信功能划分为7个层次，同时也定义了层次之间的相互关系以及各层所包括的服务及每层的功能。OSI的七层由低到高依次为：物理层、数据链路层、网络层、传输层、会话层、表示层、应用层，下三层（物理层、数据链路层、网络层）面向数据通信，而上三层（会话层、表示层、应用层）则面向资源子网，而传输层则是七层中最为重要的一层。它位于上层和下层中间，起承上启下的作用。


### 6、索引再什么情况下遵循最左前缀的规则？

在多字段进行索引的时候，会遵循以上原则


### 7、对字典d={'a':30,'g':17,'b':25,'c':18,'d':50,'e':36,'f':57,'h':25}按照value字段进行排序

```python
d={'a':30,'g':17,'b':25,'c':18,'d':50,'e':36,'f':57,'h':25}
dd=sorted(d.items(),key=lambda x:x[1])
print(dd)
```


### 8、曾经使用过哪些前端框架

react，vue，bootstrap，elementUI，Echarts


### 9、python递归的最大层数？

1000


### 10、简述事务及其特性

事务是用户定义的一个数据库操作序列，这些操作要么全做要么全不做，是一个不可分割的工作单位

事务具有4个特性：原子性、一致性、隔离性和持续性。

**1、** 原子性：事务是数据库的逻辑工作单位，事务中包括的诸操作要么都做，要么都不做。

**2、** 一致性：事务执行的结果必须是使数据库从一个一致性状态变到另一个一致性状态。

**3、** 隔离性：一个事务的执行不能被其他事务干扰。即一个事务内部的操作及使用的数据对其他并发事务是隔离的，并发执行的各个事务之间不能互相干扰。

**4、** 持续性：持续性也称永久性，指一个事务一旦提交，它对数据库中数据的改变就应该是永久性的。接下来的其他操作或故障不应该对其执行结果有任何影响。


### 11、写python爬虫分别用到了哪些模块？分别有什么用？
### 12、Python中的装饰器是什么？
### 13、什么是反射，以及应用场景
### 14、数据库的导入与导出命令
### 15、常用字符串格式化有哪几种？
### 16、python3和python2中int和long的区别
### 17、在Python中是如何管理内存的？
### 18、写出如下代码的输出结果
### 19、如果已经建立了TCP连接，但是客户端突然出现故障了怎么办
### 20、如何判断一个对象是否可调用？哪些对象是可调用对象？如何定义一个类，使其对象本身就是可调用对象？
### 21、实例方法、静态方法和类方法的区别
### 22、如何判断一个值是方法还是函数？
### 23、什么是Flask？
### 24、写一个的支持with语句的类
### 25、现有mydict和变量onekey，请写出从mydict中取出onekey的值的方法
### 26、json序列化时可以处理的数据类型有哪些？如何定制支持datetime类型？序列化时，遇到中文转成unicode，如何保持中文形式？
### 27、如何实现Redis集群
### 28、有两个字符串列表a和b，每个字符串是由逗号隔开的一些字符
### 29、Python有哪些特点和优点？




## 全部答案，整理好了，直接下载吧

### 下载链接：[全部答案，整理好了](https://www.souyunku.com/wp-content/uploads/weixin/githup-weixin-2.png)




## 最新，高清PDF：172份，7701页，最新整理

[![大厂面试题](https://www.souyunku.com/wp-content/uploads/weixin/mst.png "架构师专栏")](https://www.souyunku.com/wp-content/uploads/weixin/githup-weixin.png "架构师专栏")

[![大厂面试题](https://www.souyunku.com/wp-content/uploads/weixin/githup-weixin.png "架构师专栏")](https://www.souyunku.com/wp-content/uploads/weixin/githup-weixin.png "架构师专栏")
