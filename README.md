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
