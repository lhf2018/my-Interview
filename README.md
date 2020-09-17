# my-Interview
本项目仅仅记录一下我在2020年春招和秋招参加的部分面试面经，因为懒惰与健忘，导致只有几场面试被我记录了面经

#### 阿里云一面
* 反转链表
* 重写hashcode
* Docker底层资源隔离化机制
* Docker逃逸几种方式
* 容器安全有哪几种
* Jvm最新的垃圾回收算法优化到了什么程度
* Springcloud组件实现原理
* Spring cloud网关
* 如何实现文件全文搜索
* 简述倒排索引
* 重载和多态的区别
* CAS的全称是什么
* Object哪几种方法
* JVM为什么会出现OOM
* ConcurrentHashMap哪些地方使用了什么并发机制
* Hashcode作用，比较为什么不用equals
* 那种数据库引擎支持倒排索引
* Springboot和springcloud区别
* Dubbo框架了解吗
* Springcloud如何实现远程调用
* Serializable作用
* Dockerfile中的cmd和entrypoint区别
* 网盘项目存储使用的文件系统

#### 美团一面
* 公平锁底层如何实现
* 加权轮询平滑实现（用什么数据结构）
* 如何理解面向对象和面向过程
* Redis如何实现分布式锁
* Redis缓存击穿缓存雪崩是什么？怎么预防
* 布隆过滤器原理
* HTTP请求中301和302是什么，什么时候用这两种
* Synchronized和ReentrantLock区别
* 你一般用的虚拟机的那种垃圾回收器
* 现在的虚拟机默认什么垃圾回收器
* Cms工作过程
* 垃圾收集器中stop the world 过程
* Jvm如何对类进行加载
* 双亲委派机制了解吗？为什么要这样
* DNS服务器解析过程
* Springcloud微服务组件的作用，遇到的问题
* Git的内部结构
* 如果想对git进行操作，已经写了很多，但想恢复成远端代码，如何实现
* Git如何保存已有代码，然后对代码进行另一种更改
* atomicInteger如何实现原子操作
* 线程池中的参数
* Lsof全称
* Linux如何查一个端口被什么进程使用
* Linux如何查看一个日志的后100行
* Java 8 如何对一个list过滤 （stream流 filter）
* 如何对请求进行解析
* Mysql最左前缀匹配
* Synchronized如何对自旋进行控制
* Springboot为什么好

#### 腾讯提前批一面
* Tcp/udp区别
* 进程和线程区别
* 进程间通信的方式
* 算法：N的m次方，如何减少N乘法次数
* 操作系统中锁机制、具体实现
* 讲讲实习经历，亮点

#### 腾讯提前批二面
* 不考虑具体语言，如何设计hashtable
* 常见的hash函数
* 如何解决hash冲突
* 场景题：如何对10亿个用户的键值对数据进行查找（不适用缓存机制，不适用主从架构）

#### 作业帮一面
* 200，403，500，502，503状态代表含义
* Post get
* Cookie session区别和场景
* Arp协议
* 一致性hash原理
* 一致性hash如何解决均匀问题
* Redis底层数据结构
* 面向对象三大特性
* http请求的整个过程
* 单例的使用场景
* Aof和rdb优缺点
* 秒杀常见、保证可用、防止超卖
* Redo和undolog
* MVCC
* 二分查找
* 乐观锁和悲观锁
* Redis和mysql区别、使用场景

#### 作业帮二面 4.09
* 如何启动一个进程
* 进程和线程区别
* 什么是线程安全
* 如何解决线程安全问题
* 什么是聚簇索引和非聚簇索引
* 最左匹配原则
* 了解哪些设计模式
* 设计模式的几大原则
* mysql的事务ACID介绍
* 数据库索引的底层原理
* B树和B+树的区别
* JVM的垃圾回收机制
* TCP如何预防阻塞（拥塞避免和流量控制）
* 输入一个url会经过哪些步骤

#### 阿里新零售一面4.06
* 常见的限流算法和框架
* 论坛登陆需要考虑的安全性问题（基于项目）
* 现在数据库一般采用怎么样方式对数据加密
* mybatis如何考虑考虑sql注入
* mybatis中#和$区别和分别在什么时候使用
* redis为什么快
* redis数据除了在内存中，可以在磁盘中吗（持久化）
* spring依赖注入有哪几种方式
* 除了autowired还有哪种（resource）
* autowired和resource的区别
* 说一下锁的可重入
* 说一下读过哪些JDK源码
* mysql的索引类型
* 最左前缀原则的使用细节

#### 字节跳动提前批一面7.12
* 实习经历
* ssm指什么
* git rebase和git merge区别
* TCP特点
* tcp拥塞控制
* 传输层有什么协议
* concurrenthashmap和hashmap区别，concurrenthashmap如何计算size
* mysql的几种隔离级别，默认实现
* spring生命周期
* spring中bean调用构造器在哪个阶段
* sql慢查询的原因
* 线程和进程的区别
* 多线程的好处，单核cpu呢
* linux 查看端口映射
* jvm中几种垃圾回收器区别
* 什么时候用cms，什么时候用G1

#### 字节跳动提前批二面7.15
* 为什么四次挥手比三次握手多一次
* cap代表什么
* leetcode24
* 局域网访问公网的过程
* 网络层的各种协议
* 各种攻击方式，如跨站脚本攻击
* 什么是协程
* inner join， left join ，right join
* 什么是幂等

#### 百度提前批一面7.15
* 实习经历
* http为什么使用tcp连接
* tcp和udp关系
* tcp如何流量控制
* 常见的排序算法
* 排序算法的时间复杂度
* 不同排序的使用场景
* arraylist和linkedlist分别使用场景
* 进程和线程区别
* 进程通信和线程通信
* JVM垃圾回收过程
* redis zset如何保证顺序
* redis为什么qps高
* redis为什么单线程机制
* mysql有什么存储引擎
* innodb和myisam区别
* 什么时候采用innode和myisam
* 为什么b+树采用B+树而不是b树
* java有哪几种map实现，区别
* 为什么hashmap采用红黑树而不是b树b+树
* 深度优先遍历和广度优先遍历的使用场景

#### 百度提前批二面7.22
* 设计模式知道哪些，设计模式的几大原则
* 操作系统如何管理磁盘，为什么删除了以后还能被恢复
* String a="a"和String a=new String("a")区别
* 实现一个LRU
* 线程的内存空间能通信吗
* 有序集合和无序集合
* String和stringbuilder、stringbuffer区别
* redis在项目中使用场景
* byte在底层怎么存储
* treemap
* redis为什么采用跳表而不是红黑树
* jvm各种
* 知道桶排序吗
* 红黑树像什么排序
* innodb和myziam区别
* double是多少位的
* Integer和int区别
* aop是什么
* 论坛项目如何管理验权，确保用户是当前用户
* docker在项目中如何使用，介绍一下docker
* docker之间如何通信
* elasticsearch同步的时延是什么原因造成
* 如何理解事务

#### 好未来提前批二面7.29
* synflood怎么预防
* 自动拆箱封箱
* mysql中的锁
* Integer a=new Integer();和Integer b=12;区别
* 对docker的理解
* cgoup如何实现资源隔离
* mvcc
* redis如何使用
* 缓存还知道哪些
* 三次握手的过程
* 实习中遇到最难的点
* 天池比赛
* n的全排列
* final static
* volatile作用和实现原理
* 创建对象的几种方式

#### shopee一面8.3
* LFU、LRU
* JVM模型
* hashmap线程安全问题：会出现死循环
* 数据库乐观锁和悲观锁
* redis分布式锁
* mysql的几种隔离级别
* 线程和进程区别
* 什么是协程
* 线程和进程间通信方式
* mysql几种引擎的区别
* mysql几种数据隔离机制
* 什么时候索引失效
* 数据库MVCC
* 消息队列的使用场景
* TCP和UDP区别
* TCP如何保证可靠性
* 什么情况下适合建立索引
* 线程池的参数
* 线程池的工作过程
* 线程池的拒绝策略
* redis zset使用场景、底层实现
* redis持久化机制
* select、poll、epoll原理、时间复杂度
* epoll ET、LT模式
* 不同的垃圾回收器之间的区别，如cms和g1
* 内存泄漏和内存溢出区别
* 什么情况下会产生死锁

#### shopee二面 8.7
* 二叉搜索树的删除
* mysql的引擎和有什么特点
* 操作系统的文件系统
* HTTP各类状态码和具体的作用
* 有什么爱好
* 对未来工作的要求

#### 用友一面 8.12
* IO模型有哪些
* IO多路复用
* 如何排查程序变慢
* 如何排查死锁
* mybatis中的设计模式有哪些
* 阿里redis如何部署的
* 阿里TDDL如何分库分表的逻辑
* 实习公司用过哪些中间件和微服务
* 用过哪些缓存 guava、redis
* Java IO讲一下
* 字节流和字符流的区别
* 单例模式如何破坏，反射如何破坏，如何解决
* 如何理解线程安全
* concurrenthashmap 1.7和1.8区别
* jvm的基本构造
* 创建一个静态集合是否会出现内存泄漏
* 写代码：判断是否为奇数

#### 跟谁学 8.20
* tcp、udp场景
* 不同编码走索引嘛
* b树和b+树区别
* 项目里如何封装对象
* 讲一下反射

#### 猿辅导 8.21
* tcp为什么三次握手
* 快照读和当前读
* for update

#### 腾讯pcg一面 8.25 
* tcp dump
* tcp头部都有什么字段
* 拥塞窗口值是发送方还是接收方
* 联合索引内部结构
* b+树非叶子节点内部怎么存储？数组链表？
* redis hash和set key区别
* 跳表的时间复杂度
* 跳表如何插入数据
* 桶排序
* redis主从

#### 快手一面
* mysql发送语句会经过哪些组件
* mysql优化器是如何优化的
* JDK框架有哪些设计模式
* float底层如何实现
* 计算机如何表示浮点数
* innodb如何实现事务
* mysiam和innodb的区别
* 单例模式如何防止序列化的问题
* 线程池都默认实现哪种工作队列
* 实现一个LRU
* 如何实现线程安全的list
* TreeSet和HashSet如何判断两元素相等
* tcp为什么三次握手四次挥手
* 几种IO模型区别
* synchronized和Reentrantlock区别
* threadlocal的实现原理
* 弱引用和软引用
* binlog的作用
* timestamp和datetime的区别
* char varchar后面的数字含义
* utf8和utf8mb4区别

##### 美团一面
* 为什么用这些作为gcroot
* 什么是虚拟内存
* 什么是事务
* 五种IO模型
* 进程间的通信方式具体解释一下
* innodb为什么使用自增主键

##### 腾讯二面 9.2
* 红黑树和B树，B+树区别
* 内联函数
* tcp如何区分两个报文
* arp如何解析地址
* 硬链接和符号连接区别 inode

##### 字节一面 9.7
* 线程切换需要保存啥
* 调用方法如何入栈出栈，过程
* 什么情况下会切换线程
* 代码如何编译为可运行的机器码
* tcp粘包原因，怎么解决
* http请求报文结构
* mysql的工作过程
* concurrenthashmap结构

##### 字节二面 9.7
* 502错误如何排查

##### 其他面试问题总结
* 线程池如何复用线程
* 如何终止线程，需要注意什么
* docker可能出现镜像很大，原因
* 什么是contextswitch
* redis在持久化过程中如何处理新请求
* redis持久化设置参数
* redis的多路复用模型
* tomcat是双亲委派吗
* tomcat的类加载机制
* 线程饥饿和活锁
* redis事务
* 单链表排序
* 如何解决多个mysql之间的复制binlog造成的循环
* redis集群基于什么原理
* 选举机制
* 多态概念
* 慢sql排查
* 重载发生在什么时候
* 热点key怎么解决
* 介绍一下流
* jni