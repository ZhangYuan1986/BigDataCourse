# 大数据技术学习大纲

## 1、基础工具

### 1.1、GIT基础操作

新建项目文件夹，进入文件夹，初始化仓库：git init，编码，添加文件信息： git add .，确认添加信息：git commit -m"描述信息"，查看详细日志信息：git log，查看简略日志信息：git log --oneline，版本回滚:git reset --hard 版本号 等等

参考学习地址：https://www.liaoxuefeng.com/wiki/896043488029600 和 https://www.bilibili.com/video/BV1sM4y1M7Bd

### 1.2、IDEA开发工具

基本使用、常用设置、常用快捷键、Maven操作
参考学习地址：https://github.com/judasn/IntelliJ-IDEA-Tutorial

### 1.3、Markdown语法

基本语法使用
参考学习地址：https://www.yuque.com/yuque/gpvawt/lnobo9

## 2、基础运维知识

### 2.1、Linux基础知识

Linux 常用命令及配置
系统管理和故障排查
Vim 基本操作
搭建并维护基于 Linux 的常用服务
参考学习地址：https://time.geekbang.org/course/intro/100029601?tab=catalog

### 2.2、Shell基础知识

自定义变量与特殊变量
运算符、条件判断、流程控制
系统函数&自定义函数
常用工具命令
常用正则表达式
参考学习地址：https://time.geekbang.org/course/intro/100029601?tab=catalog 和 http://c.biancheng.net/shell/

## 3、理论知识学习

### 3.1、分布式基础理论

CAP定理：一致性、可用性、分区容忍性
Base理论：BASE理论是对CAP中的一致性和可用性进行一个权衡的结果，理论的核心思想就是：我们无法做到强一致，但每个应用都可以根据自身的业务特点，采用适当的方式来使系统达到最终一致性。
ACID四要素：原子性、一致性、独立性、持久性
Raft算法：Raft共识算法、Raft选举算法、Raft与CAP、Raft与ACID、Raft在Etcd中的实现 https://raft.github.io/
Paxos算法：《从Paxos到Zookeeper》和 https://zh.wikipedia.org/wiki/Paxos%E7%AE%97%E6%B3%95

### 3.2、分布式基础理论

聚合数据模型
分布式模型
分布式一致性与共识
分布式事务与共识

参考学习地址：https://seata.io/zh-cn/ 和 《数据密集型应用系统设计》

### 3.3、大数据架构模型

OLTP架构，OLAP架构，HTAP架构

参考学习地址：https://www.bilibili.com/video/BV1tr4y1V7mQ/?spm_id_from=333.337.search-card.all.click

### 3.4、大数据处理模型

批处理，流处理，批流一体
参考学习资料：《Flink基础教程(图灵出品)》 和 《Spark权威指南》 ，Spark https://www.bilibili.com/video/BV11A411L7CK，Flink https://www.bilibili.com/video/BV133411s7Sa

### 3.5、大数据建模理论

数据仓库
数据湖：《大数据湖最佳实践》
湖仓一体

参考学习地址：https://www.bilibili.com/video/BV1AT411j7hu

## 4、Java基础知识

### 4.1、基础知识

**Maven：**
Maven环境搭建，本地仓库&中央仓库，自动部署&持续继承&持续部署，创建Web工程

参考学习地址：https://www.bilibili.com/video/BV12q4y147e4

**Java基础语法：**
分支结构if/switch，方法重载，方法声明和调用，循环结构for/while/do while，数组的使用，参数传递等等

参考学习地址：https://www.bilibili.com/video/BV1Kb411W75N

**面向对象编程：**

封装、继承、多态、构造器，异常处理机制，super、this、Object类，枚举、注解，抽象类、接口、内部类，常有基础API，集合List/Set/Map，泛型、集合等等

参考学习地址：https://www.bilibili.com/video/BV1Kb411W75N

**Lambda表达式**

参考学习地址：https://www.bilibili.com/video/BV1Gh41187uR/?spm_id_from=333.337.search-card.all.click

**StreamAPI**

参考学习地址：https://www.bilibili.com/video/BV1Gh41187uR?p=12

### 4.2、Springboot



### 4.3、Springcloud



### 4.4、Mybatis

代码生成器，CRUD接口，条件构造接口，Mapper文件编写，常见插件使用等等

参考学习地址：https://baomidou.com/

## 5、SQL

**Mysql**

分组查询、Join查询、子查询，Union查询、函数，DML语言、DDL语言、DCL语言，事务的隔离级别等，分库分表、主从复制、视图，索引和优化、存储引擎等等

参考学习地址：https://www.bilibili.com/video/BV1iq4y1u7vj/

## 6、数据采集

### 6.1、Flume

Flume架构， Agent内部原理，事务，安装部署，自定义Source，自定义Sink等等

参考学习地址：https://www.bilibili.com/video/BV1wf4y1G7EQ

### 6.2、DataX

DataX架构原理，DataX部署，DataX使用，DataX优化等等

参考学习地址：https://www.bilibili.com/video/BV1H44y1x76X

### 6.3、Kafka

基础架构，生产者消息发送流程，异步发送API，同步发送API，生产者分区策略，数据可靠性，数据去重，数据有序，数据乱序，节点服役和退役，Leader选举流程，文件存储机制，高效读写原理，消费策略，数据积压，Kafka-Kraft模式等等

参考学习地址：https://www.bilibili.com/video/BV1vr4y1677k

## 7、大数据

### 7.1、技术栈

**Hadoop**

Hadoop生态介绍，Hadoop运行模式，源码编译，HDFS文件系统底层详解，DN&NN工作机制，HDFS的API操作，MapReduce框架原理，数据压缩，Yarn工作机制等等

参考学习地址：https://www.bilibili.com/video/BV1Qp4y1n7EN

**Redis**

安装配置，Redis的五大数据类型，Jedis，持久化，RDB，AOF等等

参考学习地址：https://www.bilibili.com/video/BV1cr4y1671t/?spm_id_from=333.337.search-card.all.click

**Zookeeper**

Zookeeper数据结果，内部原理，选举机制，Stat结构体，分布式安装部署等等

参考学习地址：https://www.bilibili.com/video/BV1to4y1C7gw/

### 7.2、计算引擎

**Hive**

Hive架构原理，安装部署，DML数据操作，查询语句，Join&排序，分桶&函数，压缩&存储，调优等等

参考学习地址：https://www.bilibili.com/video/BV1EZ4y1G7iL/

**Spark**

安装部署，RDD概述，编程模型，持久化&检查点机制，DAG，算子详解，累加器&广播变量，SparkSQL，DataFrame，DataSet，自定义UDF&UDAF函数，SparkSQL调优，数据倾斜处理，小文件处理，大表join大表，大小表MapJoin等等

参考学习地址：https://www.bilibili.com/video/BV11A411L7CK

**Flink**

运行时架构，数据源Source，Window API，Water Mark，状态编程，Flink SQL，Table API，CEP复杂事件处理，Flink优化等等

参考学习地址：https://www.bilibili.com/video/BV133411s7Sa

### 7.3、数据查询

SparkSQL，FlinkSQL

参考学习地址：https://www.bilibili.com/video/BV11A411L7CK 和 https://www.bilibili.com/video/BV133411s7Sa

### 7.4、即席查询

**Doris**

Doris编译域安装，集群扩容和缩容，数据划分，数据模型，动态分区，Rollup，物化视图，表的创建修改和删除，数据导入导出，查询设置，Join查询，集成Spark，集成Flink，企业级优化，数据备份和恢复等等

参考学习地址：https://www.bilibili.com/video/BV15S4y1h7Kt

### 7.5、数据可视化

**Superset**

参考学习地址：https://www.bilibili.com/video/BV1SL4y1a7WK

### 7.6、任务调度

**DolphinSchduler**

参考学习地址：https://www.bilibili.com/video/BV1sa411x7Ep

### 7.7、元数据管理

**Atlas**

安装部署，元数据管理等等

参考学习地址：https://www.bilibili.com/video/BV1jA411F76d

### 7.8、数据开发

**Hue**

安装部署，SQL查询等等

参考学习地址：https://www.bilibili.com/video/BV1Fa411A7JY

### 7.9、数据安全

OpenLdap，Ranger

参考学习地址：
https://www.bilibili.com/video/BV1Pa4y1e7Ez/?spm_id_from=333.337.search-card.all.click
https://www.bilibili.com/video/BV1XL411V725/?spm_id_from=333.337.search-card.all.click

## 8、项目实战

### 8.1 电商数仓（离线）

参考学习地址：https://www.bilibili.com/video/BV1AT411j7hu

### 8.2 Flink实时数仓

参考学习地址：https://www.bilibili.com/video/BV1Ju411o7f8/
