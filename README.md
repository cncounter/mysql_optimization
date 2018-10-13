# mysql_optimization

# MySQL调优相关


This chapter explains how to optimize MySQL performance and provides examples. Optimization involves configuring, tuning, and measuring performance, at several levels. Depending on your job role (developer, DBA, or a combination of both), you might optimize at the level of individual SQL statements, entire applications, a single database server, or multiple networked database servers. Sometimes you can be proactive and plan in advance for performance, while other times you might troubleshoot a configuration or code issue after a problem occurs. Optimizing CPU and memory usage can also improve scalability, allowing the database to handle more load without slowing down.

本文通过实例来讲解如何优化MySQL性能。

性能优化主要包括: 多个层级的配置优化, 参数调优, 以及性能测量。

根据工作性质(如开发人员、DBA)，可能需要对部分SQL语句进行优化、或者对整个应用系统、数据库服务器、甚至数据库集群进行性能调优。

可以提前为性能调优做好计划, 但更多的情形, 是出现性能问题以后, 需要我们紧急进行诊断排查, 调整配置或者修正代码。

优化CPU和内存使用量, 可以让数据库在负载增加的时候, 不会降低性能, 也就是提高了 可扩展性(scalability).


## 目录

- 8.1 Optimization Overview
- 8.2 Optimizing SQL Statements     
- 8.3 Optimization and Indexes     
- 8.4 Optimizing Database Structure     
- 8.5 Optimizing for InnoDB Tables     
- 8.6 Optimizing for MyISAM Tables     
- 8.7 Optimizing for MEMORY Tables
- 8.8 Understanding the Query Execution Plan     
- 8.9 Controlling the Query Optimizer     
- 8.10 Buffering and Caching     
- 8.11 Optimizing Locking Operations     
- 8.12 Optimizing the MySQL Server     
- 8.13 Measuring Performance (Benchmarking)     
- 8.14 Examining Thread Information





原文链接: <https://dev.mysql.com/doc/refman/5.7/en/optimization.html>

开始时间: 2018年10月13日

