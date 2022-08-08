# eDialects
一个通用数据库方言工具

简介 | Intro
jDialects支持多达80多种数据库方言的DDL创建、实体源码生成、分页、函数变换、类型变换及主要的JPA注解解析功能。
它通常与JDBC工具组合使用，也可以作为其它Dao工具(如jSqlBox)的一个组成部分。

优点 | Advantages
无侵入：jDialects工作原理基于对SQL文本进行变换，不会对您现有的持久层工具产生任何影响。
依赖少：仅依赖单个jar文件, 大小约280k。
从Annotation创建DDL：提供对一些主要的JPA注解的支持
从Java方法创建DDL：提供Java方法配置来创建DDL，同样的语法也可以在运行期修改配置。
从数据库生成实体类源码：可以读取数据库结构，生成注解风格的实体类POJO或ActiveRecord实体类源码
主键生成器：提供十种主键生成器，和一个分布式主键生成器。
分页：提供跨数据库的分页方法。
函数变换：对不同的数据库解析成对应方言的函数，尽量做到一次SQL到处运行。
类型变换：对不同的数据库字段类型，提供与Java类型的互相变换。
保留字检查：提供数据库保留字检查功能。
文档 | Documentation
中文 | English

[JavaDoc](https://search.maven.org/#search%7Cga%7C1%7Ca%3A%22jdialects%22)

应用示例 | Demo
在纯JDBC中使用

在jSqlBox中使用

在MyBatis中使用

下载地址 | Download
点此去下载
或在项目pom.xml中添加：

<dependency>
    <groupId>com.github.drinkjava2</groupId>
    <artifactId>jdialects</artifactId>
    <version>5.0.13.jre8</version>  <!-- 或最新版本 -->
</dependency>
相关开源项目 | Other Projects
基于DbUtils和jDialects的持久层工具 jSqlBox
一个独立的声明式事务工具 jTransactions
一个微型IOC/AOP工具 jBeanBox
期望 | Futures
欢迎发issue提出更好的意见或提交PR，帮助完善 jDialects

版权 | License
Apache 2.0

关注我 | About Me
Github
码云
