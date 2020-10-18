---
layout: cv
title: Yong Li's CV
---
# 李勇

<div id="webaddress">
+86 18927406823 | 
<a href="s4179e1@msn.com">s4179e1@msn.com</a> |
<a href="./YongLi-CV-zh.pdf">下载PDF</a> |
<a href="./index.html">English Version</a>
</div>

## 自我评价

多年Linux平台开发经历，同时在站点可靠性工程上拥有丰富的经验

扎实而全面的技能组合，乐于分享，积极拥抱前沿技术

### 开发语言

C, Shell, Python, Golang, NodeJs, Lua

### 专业技能

云计算，操作系统，分布式系统，容器，存储，网络

## 工作经历

### 腾讯
`2019年11月至今`
**TEG - 企业IT部 [混合角色]**

为企业IT服务上云提供技术解决方案和技术咨询，主导容器化业务上云

在组织中落地站点可靠性工程，包括流程、自动化、文化等方面

参与TEG的研发效能平台（智研）的开发，提高从开发，测试到运维全生命周期的效率

`2018年12月 - 2019年11月`
**TEG - 基础架构部 [运营开发工程师]**

负责部门的CI/CD体系的建设，用于支撑腾讯云、社交业务、金融业务基层设施的发布和变更

主导RolesDB（增强版的CMDB及应用配置管理系统）和API 网关的开发和项目管理

`2018年 2月 - 2018年11月`
**TEG -基础架构部 [云存储运维工程师/SRE]**

负责腾讯云分布式存储（CBS）的日常运维，保障其可用性和稳定性

对全运维流程进行标准化，为运维自动化建立了基础

打通多个上游系统，完成了云存储集群部署的自动化

### 甲骨文
`2016年11月 - 2018年 2月` **架构和性能服务 [站点可靠性工程师(SRE)]**

为Oracle的基础架构设施提供解决方案和技术支持，参与AI OPS平台的开发来保障服务的可靠性

参与P1 on call轮值来支持Oracle的关键服务，负责Oracle Linux，Oracle VM，以及ZFS存储的故障恢复和原因分析。

`2012年10月 - 2016年10月`
**全球技术支持中心 [Linux技术支持工程师]**

为Oracle Linux和Oracle VM提供技术支持，包括但不限于：故障排查，宕机原因分析，以及性能调优

问题管理：按照问题的严重程度和服务SLA跟进和处理问题，根据需要上升获取更多的资源来推动问题的解决

知识管理：维护内部测试环境来重现和验证问题，为这些问题创建知识库文档


### 傲冠软件
`2010年 5月 - 2012年 9月`
**研发中心 [软件工程师]**

傲冠软件是一家基于开源技术的系统集成商，专注于集群系统、虚拟化、以及IT服务

参与公司多个产品的研发，包括集群和容灾软件HADR V2.6， 客户端HGC图形化配置工具等

参与开源项目[php-libvirt](https://libvirt.org/git/?p=libvirt-php.git;a=search;s=Lyre;st=author)的开发，并把它集成到傲冠的异构虚拟化管理平台HGCCP V2.0 中

## 项目介绍

### 腾讯
__企业IT容器服务平台__ (Helm/Golang)

While migrating our containerized applications to Tencent Kubernetes Engine, we integrate it with multiple internal service for access control, namespace isolation, etc. As a Solution Architecture I lead the building of this platform, developed the procedure and best practice in application migration and deployment.

As a Consultant, I share the knowledge on docker and kubernetes via lectures, trainings, demos, and articles. I also responsible for migrating our critical services like IAM into kubernetes.

As a developer, I created a Helm Chart template (which implemented our best practice) and CI/CD plugin to simplify application deployment.

__企业IT Linux基础镜像__ (Bash/Golang)

As a part of Site Reliability Engineering, we deliver our standard runtime by creating a Linux Base image. A modular framework were developed to automate the image creation, as well as daily routine inspections to discover the non-standard configuration for online systems.

I purposed these configuration and best practice, developed the scripts to build Linux images, as well as the dashboard for routine inspections.

__RolesDB__ (Python Flask/MongoDB)

RolesDB is an Instance and Configuration Management System, aim to support the CI/CD pipeline for large scale underlying cloud infrastructure (storage, load balancer, etc). Its label based implementation allow user organize instance easily while  filter them preciously.

I am the architecture and lead programmer for this project.

__CBS云存储自动上架服务__ (Python Flask/ETCD)

This project bridged gaps between multiple upstream services to automate custer deployment, reducing the time to deploy a cluster from 30 minutes (in an ideal condition) to 5 minutes at average. It greatly improve the productivity as we were deploying new clusters every day.

I designed and implemented the whole system.

### 甲骨文

__Zbroker分布式协调服务__ (Python/Zookeeper)

ZBroker Coordination Service is a distributed coordination system, it's a part of an AI ​​Ops platform for self healing. When a moving part in the cloud infrastructure fails, multiple self recovery modules may be triggered at the same time, which result in conflict. For example, several module will try to recover a same database. ZBroker is based on zookeeper and uses a custom read-write lock to resolve these conflicts.

I am responsible for the design and development of this service.

__Bug Auto Triage__ (Python/Bash)

Operation team file bugs for triage whenever components failure, 40% of these bugs were known issues such as hardware failures, software bugs, or incorrect configuration. This project provide a modular framework that analyzes the bug description, attachments, call stacks, and generate a report showing the similarity with other known bugs.

I designed and developed the framework, also implemented the hardware fault module.

### 傲冠软件

__傲冠高可用和容灾软件__ (C/Bash)

Skkybility HADR is a Disaster Recovery solution based on a existing two-node High Availability cluster, and integrates open source solution DRBD(similar to a RAID-0 over network) for disaster recovery. To mitigate the performance impact caused by limited internet bandwidth, a proxy module were developed to cache its I/O traffic, and send to its peer asynchronously.

I am responsible for the development of Web Configuration Server, and part of the proxy server.

## 个人项目

[Live Sequence Protocol](http://code.poetpalace.org/cgit/p1/tree) (Golang): a transport protocol build on top of UDP, implemented some TCP-like features, including sliding window, retransmission, heartbeat, and delivery order.

[Iputils](http://git.poetpalace.org/cgit.cgi/iputils/tree) (Python): a very simple implementation of tcpdump, ping, and traceroute.

[libwp](http://git.poetpalace.org/cgit.cgi/libwp/tree) (C): wrapper for the most common libc, linux, and POSIX function, also contain some frequently used data structures and sorting algorithms.

## 文章

Multiple articles published on [WeChat Public Account](https://cloud.tencent.com/developer/column/79283), in a variety of technical fields.

Comment for [ETCD's Raft implementation](https://github.com/4179e1/etcd/tree/master/contrib/raftexample/doc)

A Lecture on distributed system, specially for [PAXOS, the Distributed Consensus Protocol](http://t.poetpalace.org/misc/paxos.pptx)

Translation of *Randy Meyers'* [The New C](http://misc.poetpalace.org/C99/), which introduce features of C99

## 教育经历

`2004年 9月 - 2009年 7月`
**深圳大学**

工学学士(计算机科学与技术)

## 证书

`2020年 4月`
__腾讯云架构工程师__

`2010年 8月`
__Red Hat Certified Engineer (RHEL5)__

`2006年 6月`
__CET-4__


<!-- ### Footer

Last updated: Oct 202CET0 -->