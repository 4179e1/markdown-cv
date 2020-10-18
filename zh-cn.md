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

在把容器化服务迁移到Tencent Kubernetes Engine时，我们需要集成公司的内部系统以提供权限控制，发布变更等功能。作为解决方案架构师我主导了这个平台的开发，提供了业务迁移部署的流程和最佳实践

作为技术顾问，我通过演讲、培训、demo、文档等多种方式分享了docker和kubernetes的知识，并负责把IAM等关键服务迁移到kubernetes中

作为开发者，我把最佳实践封装成一个Helm Chart模板，并开发了对应CI/CD流水线插件来简化服务的部署和发布

__企业IT Linux基础镜像__ (Bash/Golang)

作为站点可靠性工程的基础，我们通过创建Linux基础镜像来提供一个标准化的运行时环境，开发了一个模块化的框架了支持自动化镜像生成，并通过定时的选件发现线上的非标准配置

我编写了这些配置和最佳实践的标准，开发了标准化脚本和巡检看板

__RolesDB__ (Python Flask/MongoDB)

RolesDB时一个实例和配置管理系统，用于支撑公有云底层的大规模基础设施的CI/CDl流水线。它把分散在多个不同层次的配置信息整合到同一个系统中，包括CMDB中的配置管理项，OSS中的业务属性，以及自定义的Key Value配置项等。这些属性统一呈现为标签键值对，为其他组件如发布系统，监控系统等提供了设备筛选的功能。RolesDB另外提供了应用配置管理功能，发布系统从中获取配置数据，并把应用的配置模板渲染成实际的配置文件。

我是RolesDB的主要设计者和开发者。


__CBS云存储自动上架服务__ (Python Flask/ETCD)

该服务打通了上游多个不同系统，提供了一个后台服务和命令行工具代替了原来需要多个人工执行的操作，把部署一个集群的时间从平均30分钟降到到5分钟左右。

我负责该项目的设计和开发

### 甲骨文

__Zbroker分布式协调服务__ (Python/Zookeeper)

ZBroker Coordination Service是一个分布式协调系统，它是Oracle SaaS的AI Ops平台的一个基础组件，用于支撑自我恢复项目。云端的基础设施发生故障时，不同层次的自我恢复模块可能会同时触发，这些恢复模块的行为之间可能存在冲突，如多个模块都试图重启同一个数据库。ZBroker基于zookeeper，使用一个自定义的读写锁来解决这些冲突，它使用python编写。

我负责该项目的设计和开发

__Bug Auto Triage__ (Python/Bash)

在Oracle的生产环境中，运维团队会为每个故障报告一个bug，其中有约40%是已知问题如硬件故障，已知的bug，错误的配置项等。Bug Auto Triage提供了一个模块化的框架，通过不同的插件分析bug的内容，附件，call stack等信息，并最终生成一份报告表明这个bug跟其他已知问题的相似程度，帮助团队更快的定位问题的根源，或者分析问题的方向。

Bug Auto Triage 主要使用Python 和 Bash 编写，我负责编写了其主体框架，硬件故障，以及报告模块。

### 傲冠软件

__傲冠高可用和容灾软件__ (C/Bash)

Skybilitiy HADR V2.6 是一个集群和容灾的解决方案，它在双节点高可用性集群软件Skybilitiy HA 2.5的基础上，整合了开源的DRBD（可以当作是网络上的RAID1）来实现异地容灾，为了在广域网带宽不足的情况下确保I/O性能，加入了一个自研的代理模块，以异步的方式把I/O请求发送到备机。
    
我负责了web配置服务器，以及部分代理模块的开发，主要使用C语言和Bash。并全程协助客户（中兴通讯）完成该软件需求分析，测试验证，发布部署方案。


## 个人项目

[Live Sequence Protocol](http://code.poetpalace.org/cgit/p1/tree) (Golang): 一个基于UD开发的传输协议，包含滑动窗口、超时重传、保证消息顺序、心跳检测等类似TCP的特性

[Iputils](http://git.poetpalace.org/cgit.cgi/iputils/tree) (Python): 非常简单的tcpdump, ping, 以及traceroute的python实现

[libwp](http://git.poetpalace.org/cgit.cgi/libwp/tree) (C): 对stdc、linux、posix中常用函数的封装，及常用的数据结构和算法

## 文章

发表在微信公众号[云服务与SRE架构师社区](https://cloud.tencent.com/developer/column/79283)上的多篇文章，涉及多个技术领域

主题演讲：[分布式一致性协议Paxos简介](http://t.poetpalace.org/misc/paxos.pptx)

代码分析：[Etcd Raft协议的介绍和分析](https://github.com/4179e1/etcd/tree/master/contrib/raftexample/doc)

翻译作品：[《新的C语言》](http://misc.poetpalace.org/C99/) C99特性介绍


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