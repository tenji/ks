# 知识结构体系
### 设计模式（Design Pattern）
- Creational Patterns
  - [工厂模式（Factory Method Pattern）](https://github.com/tenji/ks/wiki/Factory-Design-Pattern)
  - [单例模式（Singleton Pattern）](https://github.com/tenji/ks/wiki/Singleton-Design-Pattern)
  - 建造者模式（Builder Pattern）
- Structual Patterns
  - [代理模式（Proxy Pattern）](https://github.com/tenji/ks/wiki/Proxy-Design-Pattern)
  - [装饰者模式（Decorator Pattern）](https://github.com/tenji/ks/wiki/Decorator-Design-Pattern)
  - 适配器模式（Adapter Pattern）
- Behavioral Patterns
  - [观察者模式（Observer Pattern）](https://github.com/tenji/ks/wiki/Observer-Design-Pattern)
  - 责任链模式（Chain of Responsibility Pattern）
  - [模板方法模式（Template Method Pattern）](https://github.com/tenji/ks/wiki/Template-Method-Design-Pattern)
  - [策略模式（Strategy Pattern）](https://github.com/tenji/ks/wiki/Strategy-Design-Pattern)
  - [状态模式（State Pattern）](https://github.com/tenji/ks/wiki/State-Design-Pattern)
- [SOLID (SRP, OCP, LSP, ISP, DIP)](https://github.com/tenji/ks/wiki/SOLID-Principles)
  - [DIP vs IoC vs DI](https://github.com/tenji/ks/wiki/SOLID-Principles#63-dip-vs-ioc-vs-di)
- [反应器模式（Reactor Pattern）](https://github.com/tenji/ks/wiki/Reactor-Pattern)
  - [Reactor vs Proactor](https://github.com/tenji/ks/wiki/Reactor-Pattern#%E5%85%ADreactor-vs-proactor)
  - [Thread-Based vs Event-Driven](https://github.com/tenji/ks/wiki/Reactor-Pattern#%E4%BA%94thread-based-vs-event-driven)
  - 论文：[Scalable IO in Java](https://gee.cs.oswego.edu/dl/cpjslides/nio.pdf)
  - 论文：[reactor-siemens](https://www.dre.vanderbilt.edu/~schmidt/PDF/reactor-siemens.pdf) 
- [Spring 中的设计模式](https://github.com/tenji/ks/wiki/Design-Pattrns-in-Spring-Framework)
### 系统设计（System Design）
### Linux
- [常用命令](https://github.com/tenji/ks/wiki/Linux-Cheat-Sheet)
- [Shell编程（Shell Programming）](https://github.com/tenji/ks/wiki/Unix-Shell-Programming)
  - Sed
  - Awk
  - Grep
  - [重定向（Shell Redirection）](https://github.com/tenji/ks/wiki/Input-Output-Redirection-in-the-Shell)
- Vim & Vi
- [Systemd](https://github.com/tenji/ks/wiki/Systemd)
- [Ulimit](https://github.com/tenji/ks/wiki/ulimit-Command) (max processes, max threads per process, max descriptors...)
### RESTful
RESTful是一种规范和原则，并不是一种实现方式，它更关注的是**设计**和**规范**，而不是**实现**。
- 实现框架
  - Spring MVC (JAVA)
  - [Flask](http://flask.pocoo.org/) (Python)
- RESTful API Design
  - 规范
  - 版本控制（Version Control）
  - [批量操作（Batch Op）](https://github.com/tenji/ks/wiki/RESTful-Batch-Operations)
- Swagger
  - [Swagger Editor](https://editor.swagger.io//#/)
  - Swagger UI
  - Swagger Codegen
- 数据交换格式
  - JSON
  - ProtoBuf
  - Avro
  - Thrift
### 数据结构与算法
- 基本数据结构
  - 数组
    - [前缀和 & 差分数组](https://github.com/tenji/ks/wiki/Prefix-Sum-&-Adjacent-Difference)
    - [滑动窗口](https://github.com/tenji/ks/wiki/Sliding-Window-Algorithm)
  - [链表](https://github.com/tenji/ks/wiki/Linked-List)
  - 栈
    - [单调栈（Monotone Stack）](https://github.com/tenji/ks/wiki/Monotonic-Stack)
  - 队列
  - [散列表（哈希表）](https://github.com/tenji/ks/wiki/Hash-table)
  - 并查集（Disjoint Set Union, or Union Find）
  - [二叉树](https://github.com/tenji/ks/wiki/Tree-Data-Structure)
    - [AVL 树](https://github.com/tenji/ks/wiki/AVL-Tree)
    - [红黑树](https://github.com/tenji/ks/wiki/Red%E2%80%93black-Tree)
  - 多叉树（Multi-way Trees）
    - [B 树（B-Tree）](https://github.com/tenji/ks/wiki/B%E2%80%90Tree)
    - [B+ 树（B+ Tree）](https://github.com/tenji/ks/wiki/B-Plus-Tree)
  - 堆
  - [跳表](https://github.com/tenji/ks/wiki/Skip-List)
  - [图](https://github.com/tenji/ks/wiki/Graph-Theory)
    - 网格类问题
    - [有向无环图（DAG）& 拓扑排序（Topological Sort）](https://github.com/tenji/ks/wiki/DAG-vs-Topological-Sort)
  - [Trie 树（字典树、前缀树）](https://github.com/tenji/ks/wiki/Trie)
- 基本算法
  - 递归
  - [排序](https://github.com/tenji/ks/wiki/Sorting-Algorithms)
  - [二分查找](https://github.com/tenji/ks/wiki/Searching-Algorithms)
  - [搜索](https://github.com/tenji/ks/wiki/DFS-&&-BFS)
  - 哈希算法
  - [贪心算法](https://github.com/tenji/ks/wiki/Greedy-Algorithm)
  - [分治算法](https://github.com/tenji/ks/wiki/Divide-and-Conquer-Algorithm)
  - [回溯算法](https://github.com/tenji/ks/wiki/Backtracking-Algorithm)
  - 动态规划
  - [字符串匹配算法](https://github.com/tenji/ks/wiki/String-Matching-Algorithm)
- 其它
  - [位运算](https://github.com/tenji/ks/wiki/Bitwise-Operation)
    - [十六进制的异或运算（字符串转十六进制、十进制、二进制）](https://github.com/tenji/ks/wiki/Bitwise-Operation#231-%E5%8D%81%E5%85%AD%E8%BF%9B%E5%88%B6%E7%9A%84%E5%BC%82%E6%88%96%E8%BF%90%E7%AE%97%E5%AD%97%E7%AC%A6%E4%B8%B2%E8%BD%AC%E5%8D%81%E5%85%AD%E8%BF%9B%E5%88%B6%E5%8D%81%E8%BF%9B%E5%88%B6%E4%BA%8C%E8%BF%9B%E5%88%B6)
  - [Java Stream](https://github.com/tenji/ks/wiki/Java-Stream)
  - [打表法](https://github.com/tenji/ks/wiki/%E6%89%93%E8%A1%A8%E6%B3%95)
  - [Some Memos](https://github.com/tenji/ks/wiki/Some-Memos)
### JAVA语言
- JAVAEE
  - 容器
    - Tomcat
      - [常用配置](https://github.com/tenji/ks/wiki/Tomcat-Common-Configuration)
      - 远程调试
      - [Tomcat 高并发及性能调优](https://github.com/tenji/ks/wiki/Tomcat-High-Concurrency-and-Performance-Optimization)
    - Jetty
  - 框架
    - Spring
      - Spring MVC
      - [Spring Boot](https://github.com/tenji/ks/wiki/Spring-Boot)
- JAVASE
  - 动态代理（Dynamic Proxy）
  - [嵌套类（Nested Class）](https://github.com/tenji/ks/wiki/JAVA-Inner-Classes)
  - [类加载器（ClassLoader）](https://github.com/tenji/ks/wiki/JAVA-ClassLoader)
  - SPI (Service Provider Interface)
  - 正则表达式（Regex）
    - [前瞻、后瞻](https://github.com/tenji/ks/wiki/Regex---Lookahead-and-Lookbehind-Assertsions)
  - [集合（Collection）](https://github.com/tenji/ks/wiki/%E5%85%B3%E4%BA%8E-Java-%E9%9B%86%E5%90%88)
    - [HashMap](https://github.com/tenji/ks/wiki/HashMap)
- 开发调试工具
  - Eclipse
    - 基本配置（Configuration）
    - [快捷键（Shortcuts）](https://github.com/tenji/ks/wiki/Eclipse-Shortcuts)
    - 调试
    - [插件](https://github.com/tenji/ks/wiki/Favorite-Eclipse-Plugins)（Plugins）
  - IntelliJ IDEA
    - [Shortcuts](https://github.com/tenji/ks/wiki/IntelliJ-IDEA-Shortcuts)
  - Sublime Text
    - [快捷键（Shortcuts）](https://github.com/tenji/ks/wiki/Sublime-Shortcuts)
    - [Plugins](https://github.com/tenji/ks/wiki/Sublime-Plugins)
- 项目构建
  - Maven
    - [仓库](https://github.com/tenji/ks/wiki/Introduction-to-Maven-Repositories)（仓库布局、仓库分类、仓库依赖解析机制）
    - Nexus
      - Install Nexus
      - Nexus Repositories
      - Deploy to Nexus
  - Gradle
### JAVA虚拟机（JVM）
- [内存区域](https://github.com/tenji/ks/wiki/JVM-Memory-Model)
  - [Different Ways to Measure Memory](https://github.com/tenji/ks/wiki/Different-Ways-to-Measure-Memory) (VIRT, RES, SHR, SWAP)
  - [What is Metaspace?](https://github.com/tenji/ks/wiki/Metaspace-Series)
- [垃圾回收器](https://github.com/tenji/ks/wiki/Garbage-Collection)
- 类文件与字节码
- 编译与代码优化
- JVM优化（JVM Tuning）
  - 命令行工具
    - [GC](https://github.com/tenji/ks/wiki/GC-Log-Analyzing)
    - [JStack](https://github.com/tenji/ks/wiki/Collecting-Thread-Dumps-Using-Jstack "Collecting Thread Dumps Using Jstack")
    - JMap
    - JStat
    - BTrace
    - Greys
    - [Arthas](https://github.com/tenji/ks/wiki/JVM-Tuning-Using-Arthas)
  - 可视化工具
    - [YourKit](https://www.yourkit.com/)
    - JConsole
    - VisualVM
    - JProfile (Commercial Authorization)
  - [JVM调优设置](https://github.com/tenji/ks/wiki/Tuning-the-JVM-for-Performance)
### Android
  - 四大组件（Four Main Components）
    - [Activity — Activity Lifecycle, Tasks & Back Stack](https://github.com/tenji/ks/wiki/Android-Activity)
    - [Service](https://github.com/tenji/ks/wiki/Android-Service)
    - [Broadcast Receiver](https://github.com/tenji/ks/wiki/Android-BroadcastReceiver)
    - Content Provider
  - Intents
    - Types of Intent
      - Implicit
      - Explicit
    - Intent Filter
  - [Fragments](https://github.com/tenji/ks/wiki/Android-Fragment)
    - Fragment Lifecycle
    - Fragment Manager
  - [UI Resources](https://github.com/tenji/ks/wiki/Android-Resources)
    - Drawables
    - String
    - Styles
  - Threading (Message-Looper-Handler)
    - Threads
    - [Handler](https://github.com/tenji/ks/wiki/Android-Handler) / Looper / Message / MessageQueue
    - [AIDL](https://github.com/tenji/ks/wiki/AIDL-%E4%BD%BF%E7%94%A8%E8%AF%A6%E6%83%85%E5%8F%8A%E5%8E%9F%E7%90%86) / Binder
  - Architecture
    - Router
  - Unit Testing
    - Local Unit Testing
    - Instrumentation Testing
  - Static User Interface
    - View 
    - ViewGroup
    - ConstraintLayout
    - AndroidX Constraint Layout library, part of Jetpack
  - Dynamic User Interface
    - RecyclerView - 列表类的布局首选控件，性能相对 ListView 要好一些，功能也比 ListView 要多一些
    - ViewPager
    - Spinner
  - Support User Interface
    - ProgressBar - 进度条
    - Dialogs - 弹框
    - Toast & Snackbar - 提示
  - CustomView
    - Canvas
    - Bitmap
    - Paint
  - Android Jetpack
    - Foundation Components — AppCompat, Android KTX, Multidex
    - Architecture Components — LiveData, ViewModel, DataBinding, Paging, Work Manager, Navigation
    - Behaviour Components - Download Manager, Media Playback, Notification, Permissions, Preference, Sharing, Slice
    - UI Component - Animation & Transition, Android Auto, Emoji, Palette, Android TV, Android Wear
  - Storage
  - Build
    - [gradle](https://github.com/tenji/ks/wiki/Android-Gradle)
    - Debug / Release Configuration
    - 多渠道打包（国内特有）
    - ASM
  - Debugging
  - 3rd Party Library
    - Image Loading - Glide, Picasso
    - Dependency Injection - Dagger
    - Networking - Fast Android Networking Library, Retrofit
    - MultiThreading - RxJava, Coroutines
  - App Release
    - .keystore file
    - App Bundle
    - Playstore
    - 多渠道打包
    - 插件化
### 安全与加密（Security & Encryption）
- 认证
  - [Kerberos](https://github.com/tenji/ks/wiki/Kerberos-Explained)
- 数据加密
  - 对称加密
    - DES (Data Encryption Standard)
    - 3DES (Triple DES)
    - AES (Advanced Encryption Standard)
  - 非对称加密
    - [RSA (Rivest–Shamir–Adleman)](https://github.com/tenji/ks/wiki/RSA-(cryptosystem))
    - DSA (Digital Signature Algorithm)
    - ECC (Elliptic Curves Cryptography)
  - 单向加密（散列算法）
    - MD5, SHA, HMAC
  - 编码
    - [Base64](https://github.com/tenji/ks/wiki/Base64-Encoding)
    - DER (Distinguished Encoding Rules)
- [数字证书和数字签名（Digital Certificate & Digital Signature）](https://github.com/tenji/ks/wiki/Digital-Certificate-&-Digital-Signature)
- 数据完整性
  - 数据校验
- CAS
### Python语言
- Python Web Framework
  - Django
  - Flask
  - Pyramid
- 开发调试工具
  - Pycharm
### Ruby
- JRuby
### Golang
### Bat脚本
### 版本控制（Version Control）
- Git
  - [分支管理](https://github.com/tenji/ks/wiki/Git-Branching-Model)
  - [常用命令](https://github.com/tenji/ks/wiki/Git-Common-Commands)
  - Git Tips
    - [Maintaining a clean Git History](https://github.com/tenji/ks/wiki/Git-tips---Maintaining-a-clean-Git-History)
    - [Git Ref & Refspec](https://github.com/tenji/ks/wiki/Git-Ref-&-Refspec)
  - [MarkDown](https://github.com/tenji/ks/wiki/Markdown-Grammar)
    - [markdown converter](https://github.com/tenji/ks/wiki/Markdown-Converter)
  - Tools
    - [SourceTree](https://www.sourcetreeapp.com/)
    - [Tower](https://www.git-tower.com/)
    - [Github for Desktop](https://desktop.github.com/)
- SVN
- CVS
### 高并发（Concurrent, Multitasking & Multithreading）
- 操作系统原理
- [并发理论基础：并发问题产生的三大根源](https://github.com/tenji/ks/wiki/Three-Root-Causes-of-Concurrency-Problems)
- Java常用并发类（JUC, java.util.concurrent）
  - [CAS (Compare and Swap)](https://github.com/tenji/ks/wiki/Compare-and-Swap)
  - [AQS (AbstractQueuedSynchronizer)](https://github.com/tenji/ks/wiki/AbstractQueuedSynchronizer)
    - [CLH](https://github.com/tenji/ks/wiki/Craig%2C-Landin%2C-and-Hagersten)
  - [集合类](https://github.com/tenji/ks/wiki/%E5%85%B3%E4%BA%8E%E5%B9%B6%E5%8F%91%E5%AE%B9%E5%99%A8)
  - 原子类（AtomicInteger）
  - 线程池（ThreadPoolExecutor, Executor, FutureTask）
  - 锁（ReentrantLock, ReentrantReadWriteLock）
    - [Different types of locks in Java](https://github.com/tenji/ks/wiki/Different-types-of-locks-in-Java)
  - 工具类（[CountDownLatch](https://github.com/tenji/ks/wiki/Concurrent---CountDownLatch), CyclicBarrier, Semaphore）
- Thread 源码解析
### 数据库（DataBase）
  - SQL
    - MySQL
      - [Database Engines](https://github.com/tenji/ks/wiki/MySQL-Database-Engines)
      - [undolog, redolog, binlog & two-phase commit (2PC)](https://github.com/tenji/ks/wiki/undolog,-redolog,-binlog-&-two%E2%80%90phase-commit-(2PC))
    - 数据老化
    - 数据库优化
  - NOSQL
    - [HBase](https://github.com/tenji/ks/wiki/HBase-Architecture)
      - [HBase Shell](https://github.com/tenji/ks/wiki/HBase-Shell-Cheat-Sheet)
      - BulkLoad
      - [HBase Backup](https://github.com/tenji/ks/wiki/%E2%80%8BBacking-up-and-Restoring-Apache-HBase-Datasets)
      - [HBase WAL](https://github.com/tenji/ks/wiki/HBase-WAL)
      - [HBase Startup Process]()
    - MongoDB
    - Cassandra
    - DynomoDB
      - [Dynamo: Amazon's Highly Available Key-value Store](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf)
    - 数据库优化
  - ORM框架（Object-Relation-Mapping Framework）
    - Hibernate
    - MyBatis (iBatis)
    - SQLAlchemy
  - [OLTP vs OLAP vs HTAP](https://github.com/tenji/ks/wiki/OLTP-vs-OLAP-vs-HTAP)
  - [行存储vs列存储（Row vs Column Storage）](https://github.com/tenji/ks/wiki/Column-and-Row-Data-Storage)
  - [HBase vs MySQL](https://github.com/tenji/ks/wiki/HBase-vs-MySQL)
### 测试
功能测试是基于原始需求的，集成测试是基于模块交互的，在一定程度上，功能测试是**包含**集成测试的。
- LLT (Low Level Test)
  - 单元测试（Unit Test, UT）
    - [Best Practices For Unit Testing In Java](https://github.com/tenji/ks/wiki/Best-Practices-For-Unit-Testing-In-Java)
  - 集成测试（Integration Test, IT）
  - 模块系统测试（Module System Test, MST）
  - 模块间集成测试（BBIT）
- HLT (High Level Test)
  - 系统设计验证（System Design Verification, SDV）
  - 系统集成测试（System Integration Test, SIT）
  - 系统验收测试（System Verification Test, SVT）
  - Tools
    - 持续集成（Continuous Integration, CI）
      - Jenkins
    - 自动化执行工具
- 功能测试（Functional Tests）
  - Tools
- 性能测试（Performance Tests）
  - Tools
    - [JMeter](http://jmeter.apache.org/)
      - [BeanShell](https://github.com/tenji/ks/wiki/How-to-Use-BeanShell)
      - [Plugins](https://github.com/tenji/ks/wiki/JMeter-Plugins)
    - [BurpSuit](https://portswigger.net/burp/)
    - LoadRunner
- [用户验收测试](https://github.com/tenji/ks/wiki/User-Acceptance-Test)（User Acceptance Test，UAT）
  - Pre-Alpha
  - Alpha
  - Beta
  - Release Candidate (RC)
  - Release
### 网络通讯 & 网络编程（Network Programming）
- 网络模型
  - OSI参考模型
    - 物理层
    - 数据链路层
    - 网络层（Network Layer, IP、ICMP、ARP、RARP）
    - **传输层**（Transport Layer）
      - [TCP](https://github.com/tenji/ks/wiki/TCP,-Transmission-Control-Protocol)
        - 拆包、粘包、半包
        - [为什么会出现大量的 CLOSE_WAIT](https://github.com/tenji/ks/wiki/TCP,-Transmission-Control-Protocol#61-%E5%87%BA%E7%8E%B0%E5%A4%A7%E9%87%8F-close_wait-%E7%9A%84%E5%8E%9F%E5%9B%A0)
      - UDP
      - Socket
    - **会话层**（Session Layer，RPC、SQL、NFS、X WINDOWS、ASP）
    - 表示层（Presentation Layer）
    - **应用层**（Application Layer，FTP、Telnet、SMTP、HTTP、RIP、NFS、DNS、NTP、MQTT）
      - HTTP/2.0
  - TCP/IP参考模型
- 协议（Protocols）
  - SSL (TLS)
    - SSL纪录协议层（SSL Record Protocol Layer）
    - SSL握手协议层（SSL HandShake Protocol Layer）
- [IO](https://github.com/tenji/ks/wiki/JAVA-IO)
  - JAVA原生IO
    - Synchronous I/O
      - BIO
      - [NIO](https://github.com/tenji/ks/wiki/Java-NIO)
        - Buffer
        - Channel
        - [Selector](https://github.com/tenji/ks/wiki/Java-NIO-Selector)
          - [SelectionKey](https://github.com/tenji/ks/wiki/Java-NIO-Selector#%E5%9B%9Bselectionkey)
        - [BIO vs NIO](https://github.com/tenji/ks/wiki/Java-NIO#%E4%BA%8Cnio-vs-bio)
    - AIO (Asynchronous I/O)
  - IO Framework
    - [Netty](https://github.com/tenji/ks/wiki/Netty-Structure)
       - ByteBuf
       - Channel
       - ChannelPipeline, ChannelHandler
       - EventLoop, EventLoopGroup
       - Future, Promise
       - 文件传输
    - Mina
    - Grizzly
### 分布式（Distributed）
分布式计算就是通过**计算机网络**将计算工作分布到多台主机上，多个主机一起协同完成工作，**网络编程**是基础中的基础。
- [基本理论（CAP，BASE，ACID）](https://github.com/tenji/ks/wiki/Basic-Concepts-of-Distribution)
- [分布式数据复制](https://github.com/tenji/ks/wiki/Distributing-Data-Replication)
- [关于脑裂](https://github.com/tenji/ks/wiki/%E5%85%B3%E4%BA%8E%E8%84%91%E8%A3%82%EF%BC%88Split-Brain%EF%BC%89)
- 协议
  - [Lease机制](https://github.com/tenji/ks/wiki/Lease)
  - Quorum机制
  - 副本控制（primary-secondary）
  - [二阶段提交（two-phase commit）](https://github.com/tenji/ks/wiki/Two%E2%80%90Phase-Commit)
  - [三阶段提交（three-phase commit）](https://github.com/tenji/ks/wiki/Three%E2%80%90Phase-Commit)
  - paxos
  - raft
  - zab (ZooKeeper Atomic Broadcast)
- 分布式缓存
  - MemCache
  - Redis
    - [Redis Cli](https://github.com/tenji/ks/wiki/Redis-Command-Cheat-Sheet)
    - Redis Persistence
    - [Cache Breakdown, Cache Penetration, Cache Avalanche, Cache Warming](https://github.com/tenji/ks/wiki/Cache-Breakdown,-Cache-Penetration,-Cache-Avalanche,-Cache-Warming)
    - [Data Types](https://github.com/tenji/ks/wiki/Redis-Data-Types) (ZSet)
- 分布式系统协调
  - 分布式锁
  - 选主
  - ZooKeeper
    - [ZooKeeper 容灾](https://github.com/tenji/ks/wiki/Disaster-Recovery-for-ZooKeeper)
    - [zkCli](https://github.com/tenji/ks/wiki/ZKCli-Usage)
    - 提供
      - [文件系统](https://github.com/tenji/ks/wiki/ZooKeeper-FileSystem)
      - 通知机制
    - 能做
      - 命名服务
      - 配置管理
      - 集群管理
      - 分布式锁
      - 队列管理
- 一致性
- 分布式事务
- 分布式消息队列（Distributed MQ）
  - Kafka
    - [Kafka Shell](https://github.com/tenji/ks/wiki/Kafka-Shell-Usage)
    - [The actual role of Zookeeper in Kafka](https://github.com/tenji/ks/wiki/The-actual-role-of-Zookeeper-in-Kafka)
    - [Kafka Replica Protocol](https://github.com/tenji/ks/wiki/Kafka-Replica-Protocol)
    - [Kafka 扩容和缩容](https://github.com/tenji/ks/wiki/Kafka-Scale-Up-and-Scale-Down)
    - [Client and broker compatibility across Kafka versions](https://github.com/tenji/ks/wiki/Client-and-broker-compatibility-across-Kafka-versions)
    - [Kafka 跨集群同步](https://github.com/tenji/ks/wiki/Kafka-%E8%B7%A8%E9%9B%86%E7%BE%A4%E5%90%8C%E6%AD%A5---MirrorMaker)
    - [DIS Kafka Partition Migration](https://github.com/tenji/ks/wiki/DIS-Kafka-Partition-Migration)
    - [DIS vs Kafka](https://github.com/tenji/ks/wiki/DIS-vs-Kafka)
    - Consumer
    - Producer
    - [源码解析](https://github.com/tenji/ks/wiki/Kafka-Source-Code-Analysis)
    - [幂等性和事务性](https://github.com/tenji/ks/wiki/Kafka-idempotency-and-transactionality)
    - Bugs
      - [(KAFKA-8154) Buffer Overflow exceptions between brokers and with clients](https://issues.apache.org/jira/browse/KAFKA-8154)
  - Flume
    - Source
    - Sink
    - Channel
    - Plugin
- 分布式日志收集
  - Logstash
- CDC (Change Data Capture)
  - Debezium
  - Maxwell
### Message Queue（消息队列）
- [MQTT](https://github.com/tenji/ks/wiki/MQTT)
### 高可用（HA & MHA & HS）
- 高可用性
- 高可靠性
- 高扩展性
- 负载均衡（LB）
  - LVS (Linux Virtual Server)
  - Nginx
    - [Nginx for Windows](https://github.com/tenji/ks/wiki/Nginx-for-Windows)
  - HAProxy
  - [四层、七层负载均衡](https://github.com/tenji/ks/wiki/Layer-4-vs-Layer-7-Load-Balancing)
- [DFX (Design for X)](https://github.com/tenji/ks/wiki/Design-for-X)
### 云计算（Cloud Computing）
云计算是指在广域网或局域网内将硬件、软件、网络等系列资源统一起来，实现数据的计算、存储、处理和共享的一种**托管**技术。
- 分层架构
  - IaaS
    - 虚拟机（Virtual Machine）
  - PaaS
    - Docker
  - SaaS
  - BDaaS  
    - 大数据组件  
      - HDFS
      - MapReduce
      - Spark
        - Spark Core
        - Spark SQL
        - [Spark Streaming](https://github.com/tenji/ks/wiki/Spark-Streaming-Architecture)
          - [Spark Streaming + Kafka](https://github.com/tenji/ks/wiki/Spark-Streaming-with-Kafka)
      - Flink
        - Flink SQL
        - Flink Streaming
        - Connectors
          - [Flink Kafka Connector 源码解析](https://github.com/tenji/ks/wiki/Flink-Kafka-Connector-%E6%BA%90%E7%A0%81%E8%A7%A3%E6%9E%90)
      - Strom
- 框架
  - OpenStack
  - CloudStack
### 运维（Operation and Maintenance）
- 运维工具（Tools）
### 前端
- JavaScript
  - 原型链/作用域链
  - 闭包（Closure）
- 开发工具
  - WebStorm
  - HBuilder
- 代码质量
  - Code Style
  - 单元测试
    - QUnit
  - 自动化测试
    - [WebDriver](http://docs.seleniumhq.org/docs/03_webdriver.jsp)
    - [protractor](https://github.com/angular/protractor)
- 前端库/框架
  - jQuery
  - AngularJS
  - Bootstrap
- 部署流程
  - 压缩合并
  - 文档输出
  - 项目构建工具
# 面试相关（Interview）
## [Java 面试](https://github.com/tenji/ks/wiki/Java-Interview)
# 浏览器书签
# 推荐书籍
- [深入理解Java虚拟机：JVM高级特性与最佳实践.周志明](https://book.douban.com/subject/6522893/) ★★★★★
- [Netty权威指南(第2版)](https://book.douban.com/subject/26373138/) ★★★★
- [Maven实战](https://book.douban.com/subject/5345682/) ★★★★
- [TCP/IP Sockets in Java: Practical Guide for Programmers](https://www.amazon.com/TCP-Sockets-Java-Practical-Programmers/dp/0123742552) ★★★★
- [Unix Network Programming: The Sockets Networking Api (1)](https://www.amazon.com/Unix-Network-Programming-Sockets-Networking/dp/0131411551) ★★★★★
- [UNIX Network Programming, Volume 2: Interprocess Communications, Second Edition](https://www.amazon.com/UNIX-Network-Programming-Interprocess-Communications/dp/0130810819) ★★★★★
- [RESTful Web Services Cookbook: Solutions for Improving Scalability and Simplicity](https://www.amazon.com/RESTful-Web-Services-Cookbook-Scalability/dp/0596801688) ★★★★
- [High Performance Browser Networking: What every web developer should know about networking and web performance](https://www.amazon.com/High-Performance-Browser-Networking-performance/dp/1449344763) ★★★★
- [Design Patterns: Elements of Reusable Object-Oriented Software](https://www.amazon.com/Design-Patterns-Object-Oriented-Addison-Wesley-Professional-ebook/dp/B000SEIBB8) ★★★★★
