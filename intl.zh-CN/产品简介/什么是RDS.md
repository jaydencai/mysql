# 什么是RDS {#concept_pc2_lv5_tdb .concept}

阿里云关系型数据库（Relational Database Service，简称RDS）是一种稳定可靠、可弹性伸缩的在线数据库服务。基于阿里云分布式文件系统和SSD盘高性能存储，RDS 支持 MySQL、SQL Server、PostgreSQL 和PPAS（Postgre Plus Advanced Server，一种高度兼容 Oracle的数据库）引擎，并且提供了容灾、备份、恢复、监控、迁移等方面的全套解决方案，彻底解决数据库运维的烦恼。

## 学习路径图 {#section_nnr_y4j_b2b .section}

您可以通过[RDS学习路径图](https://www.alibabacloud.com/zh/getting-started/learningpath/rds)快速了解 RDS的相关概念、基础操作、进阶操作等。

## 相关概念 {#section_gbt_pd1_42b .section}

了解以下概念，将帮助您更好地选购RDS：

-   实例：实例是虚拟化的数据库服务器。您可以在一个实例中创建和管理多个数据库。
-   地域：地域是指物理的数据中心。一般情况下，RDS实例应该和ECS实例位于同一地域，以实现最高的访问性能。
-   可用区：可用区是指在某个地域内，拥有独立电力和网络的物理区域。同一地域的不同可用区之间没有实质性区别。
-   数据库引擎：RDS支持四种数据库引擎：MySQL、SQL Server、PostgreSQL、PPAS（Postgre Plus Advanced Server，高度兼容 Oracle数据库）。关于各个引擎的介绍，请参考[数据库引擎](../../../../intl.zh-CN/用户指南/快速入门.md)。
-   网络类型：您可以选择将实例创建在经典网络或VPC中。专有网络VPC（Virtual Private Cloud）是阿里云上一种隔离的网络环境，安全性比传统的经典网络更高，建议您选择VPC。
-   产品系列：分为基础版和高可用版。关于各个系列的介绍，请参考[产品系列概述](intl.zh-CN/产品简介/产品系列/产品系列概述.md)。
-   规格类型：分为通用型、独享型、独占物理机型。关于各个规格类型的介绍，请参考[实例规格概述](intl.zh-CN/产品简介/实例规格/实例规格概述.md)。

## 相关服务 {#section_r45_z21_42b .section}

-   [ECS](../../../../intl.zh-CN/产品简介/什么是云服务器ECS.md)：ECS是云服务器，可以通过内网访问RDS，实现RDS的最佳性能。ECS搭配RDS是典型的业务访问架构。
-   [Redis](../../../../intl.zh-CN/产品简介/什么是云数据库 Redis 版.md)：Redis提供持久化的内存数据库服务。当业务访问量较大时， ECS 、RDS和Redis的组合可以支持更多的读请求，同时减少响应时间。
-   [MongoDB](../../../../intl.zh-CN/产品简介/什么是MongoDB云数据库.md)：提供稳定可靠、弹性伸缩、完全兼容MongoDB协议的数据库服务。
-   [MaxCompute](../../../../intl.zh-CN/产品简介/什么是MaxCompute.md)：大数据计算服务MaxCompute（原名ODPS）是一种快速、完全托管的TB/PB级数据仓库解决方案，提供了完善的数据导入方案以及多种经典的分布式计算模型，能够快速地解决海量数据计算问题。
-   [DTS](https://help.aliyun.com/document_detail/26592.html)：您可以使用数据传输服务DTS将本地数据库迁移到云上的RDS，以及实现RDS的异地容灾。
-   [OSS](../../../../intl.zh-CN/产品简介/什么是对象存储 OSS.md)：对象存储服务OSS是阿里云提供的海量、安全、低成本、高可靠的云存储服务。

## 如何使用RDS {#section_rgz_gg1_42b .section}

您可以通过多种方式使用RDS：

-   [控制台](https://rdsnew.console.aliyun.com)：提供可视化的Web界面，方便您管理RDS实例。您可以通过控制台进行实例创建、网络设置、数据库创建、账号创建等操作。
-   [API](../../../../intl.zh-CN/API参考/使用API/API概览.md)：您也可以通过调用API来管理RDS实例，控制台上所有的操作都可以通过调用API来实现。
-   客户端：RDS兼容原生的数据库协议，您可以使用通用的数据库客户端工具访问RDS实例。例如，MySQL-Front、SSMS（SQL Server Management Studio）、pgAdmin等。

## RDS定价 {#section_kzx_jg1_42b .section}

请参考[收费项目及计费方式](../../../../intl.zh-CN/产品定价/收费项目及计费方式.md)。

