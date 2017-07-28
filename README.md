# 知识结构体系
### 设计模式（Design Pattern）
- Creational Patterns
  - 工厂模式（Factory Method Pattern）
  - 单例模式（Singleton Pattern）
  - 建造者模式（Builder Pattern）
- Structual Patterns
  - 代理模式（Proxy Pattern）
- Behavioral Patterns
  - 观察者模式（Observer Pattern）
  - 责任链模式（Chain of Responsibility Pattern）
  - 模板方法模式（Template Method Pattern）
### Linux
- [常用命令](https://github.com/tenji/ks/wiki/Linux-Cheat-Sheet)
- Shell编程（Shell Programming）
  - Sed
- Vim & Vi
### RESTful
RESTful是一种规范和原则，并不是一种实现方式，它更关注的是**设计**和**规范**，而不是**实现**。
- 实现框架
  - Spring MVC (JAVA)
  - [Flask](http://flask.pocoo.org/) (Python)
- RESTful API Design
  - 规范
  - 版本控制（Version Control）
  - 批量操作（Batch Op）
### JAVA语言
- JAVAEE
  - 容器
  - 框架
    - Spring
      - Spring MVC
- 开发调试工具
  - Eclipse
    - 基本配置（Configuration）
    - 快捷键（Shortcuts）
    - 调试
    - 插件（Plugins）
  - IntelliJ IDEA
  - Sublime Text
    - 快捷键（Shortcuts）
### JAVA虚拟机（JVM）
- [内存区域](https://github.com/tenji/ks/wiki/JVM-Memory-Model)
- 垃圾回收器
- 类文件与字节码
- 编译与代码优化
- JVM优化（JVM Tuning）
  - GC
  - JStack
  - JMap
  - JStat
### 安全与加密（Security & Encryption）
- 认证
  - [Kerberos](https://github.com/tenji/ks/wiki/Kerberos-Explained)
- 数据加密
  - 对称加密
  - 非对称加密
- 数据完整性
- CAS
### Python语言
### 版本控制（Version Control）
- Git
  - [分支管理](https://github.com/tenji/ks/wiki/Git-Branching-Model)
  - [常用命令](https://github.com/tenji/ks/wiki/Git-Common-Commands)
  - [MarkDown](https://github.com/tenji/ks/wiki/Markdown-Grammar)
  - Tools
    - [SourceTree](https://www.sourcetreeapp.com/)
    - [Tower](https://www.git-tower.com/)
    - [Github for Desktop](https://desktop.github.com/)
- SVN
- CVS
### 高并发（Multithreading）
### 数据库（DataBase）
  - SQL
    - MySQL
    - 数据老化
    - 数据库优化
  - NOSQL
    - HBase
      - [HBase Shell](https://github.com/tenji/ks/wiki/HBase-Shell-Cheat-Sheet)
    - MongoDB
    - Cassandra
    - 数据库优化
  - ORM框架（Object-Relation-Mapping Framework）
    - Hibernate
    - MyBatis (iBatis)
    - SQLAlchemy
  - [行存储vs列存储（Row vs Column Storage）](https://github.com/tenji/ks/wiki/Column-and-Row-Data-Storage)
### 测试
功能测试是基于原始需求的，集成测试是基于模块交互的，在一定程度上，功能测试是**包含**集成测试的。
- LLT
  - 单元测试（Unit Test, UT）
  - 集成测试（Integration Test, IT）
  - 模块系统测试（Module System Test, MST）
  - 模块间集成测试（BBIT）
- HLT
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
    - [BurpSuit](https://portswigger.net/burp/)
    - LoadRunner
### 网络通讯&网络编程（Network Programming）
- 网络模型
  - OSI参考模型
    - 网络层（Network Layer，IP、ICMP、ARP、RARP）
    - 传输层（Transport Layer，TCP、UDP）
  - TCP/IP参考模型
- 协议（Protocols）
  - SSL (TLS)
    - SSL纪录协议层（SSL Record Protocol Layer）
    - SSL握手协议层（SSL HandShake Protocol Layer）
- IO
  - BIO
  - NIO
  - Netty
  - Mina
  - Grizzly
### 分布式
分布式计算就是通过**计算机网络**将计算工作分布到多台主机上，多个主机一起协同完成工作，**网络编程**是基础中的基础。
- 分布式缓存
  - MemCache
  - Redis
- 分布式系统协调
  - 分布式锁
  - 选主
  - ZooKeeper
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
### 高可用（HA&MHA&HS）
- 高可用性
- 高可靠性
- 高扩展性
- 负载均衡
  - Nginx
  - HAProxy
### 消息队列（Message Queue）
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
- 框架
  - OpenStack
  - CloudStack
### 运维（Operation and Maintenance）
- 运维工具（Tools）

# 浏览器书签
# 推荐书籍
- [深入理解Java虚拟机：JVM高级特性与最佳实践.周志明](https://book.douban.com/subject/6522893/)★★★★★
