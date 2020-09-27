---
layout: cv
title: Yong Li's CV
---
# Yong Li (李勇)

<div id="webaddress">
+86 18927406823 | 
<a href="s4179e1@msn.com">s4179e1@msn.com</a>
</div>

## Specialization

10 years of development experience on Linux,

also have rich experience in Site Reliability Engineering.

Solid and comprehensive skill set, like to share,

and keen to embrace leading-edge technologies.

### Programming
C, Shell, Python, Golang, NodeJs, Lua

### Skill
Cloud Computing, Operating System, Distributed System, Container, Storage, and Networking

## Occupation

### Tencent
`Nov 2019 – Now`
**Enterprise IT [Solution Architecture]**

Provide technical solution and consultant service while migrating IT service to Tencent Cloud.

Lead the building of container service platform (based on Tencent Kubernetes Engine).

Implement Site Reliability Engineering to improve service quality, including procedure, automation, and culture.

Participant in development of Business Group’s R&D platform to improve the productivity of entire software R&D lifecycle.

`Dec 2018 – Nov 2019`
**Cloud Foundation Department [Software Engineer]**

Responsible of the development of CI/CD system, to support the Tencent cloud infrastructure, including block storage, database, and finance technology.

Lead the development of RolesDB (a configuration management system, see project description below)

`Feb 2018 – Nov 2018`
**Cloud Foundation Department [Site Reliability Engineer]**

Responsible for the operation of Tencent Cloud Block Storage, ensure its availability and reliability

Standardize the entire operation procedure, leverage CI/CD pipeline to upgrade existing clusters

Developed system to automate new cluster deployment, by bridging gaps between multiple upstream systems.

### Oracle
`Nov 2016 – Feb 2018` **Architecture and Performance Service [Site Reliability Engineer]**

As a member of Architecture and Performance Service, provide solutions and technical support for Oracle’s infrastructure, participate in the development of AI Ops platform to ensure service reliability.

Take on call shift to support Oracle production environment, including public cloud. Responsible for critical service recovery and root cause analysis for Oracle Linux, Oracle VM, and ZFS Storage.

`Oct 2012 – Oct 2016`
**Global Support Center [Technical Support Engineer]**

As a member of , provide technical support for Oracle Linux and Oracle VM, including but not limited to troubleshooting, crash root cause analysis, and performance tuning.

Problem Management: Respond to solve customers’ problem according to severity level and SLA, escalate and engage more resource if needed.

Knowledge Management: maintain testing environment to simulate and reproduce customers problem and deliver multiple notes in knowledge base.

### Skybility
`May 2010 – Sep 2012`
**Research & Development Center [Software Engineer]**

Skybility is a system integration provider, focus at HA Cluster, Virtualization, and IT services.

Participate in development of multiple products, including High Availability Cluster and Disaster Recovery system, Linux based thin client system, etc.

Participate in the development of open source project [php-libvirt](https://libvirt.org/git/?p=libvirt-php.git;a=search;s=Lyre;st=author) and integrate it into Skybility’s heterogeneous virtualization management platform.

## Projects

### Tencent
__Enterprise IT Container Platform__ (Helm/Golang)

Developed configuration standard and best practice, and base image for operating system(Linux & Window); Discover and fix non-standard configuration for online systems via automatic routine inspections. 

__Enterprise IT Linux Base Image__ (Bash/Golang)

Lead the building of container service platform (based on Tencent Kubernetes Engine) and integrated it with multiple internal services like configuration management, service discovery, monitoring, and logging. Along with the highly credential data protection requirement, provide a comprehensive solution to migrate existing service to containers.

Participant in Business Group’s R&D platform -- a joint project involves multiple departments aim to improve the productivity of entire software R&D lifecycle, from development, testing, deployment, to operation. Responsible for the CI/CD sub-system development, also provide patches and advice to other sub-systems. 

__RolesDB__ (Flask/MongoDB)

RolesDB is a Instance and Configuration Management System, aim to support the CI/CD pipeline for large scale underlying cloud infrastructure (storage, load balancer, etc). Its label based implementation allow user to filter instance preciously with flexibility.

I am the architecture and lead programmer for this project.

__Cloud Block Storage Deployment__ (Flask/ETCD)

This project bridged gaps between multiple upstream services to automate custer deployment, reducing the time to deploy a cluster from 30 minutes (in an ideal condition) to 5 minutes at average. It greatly improve the productivity as we were deploying new clusters every day.

I designed and implemented the whole system.

### Oracle

__Zbroker Coordination Service__ (Python/Zookeeper)

ZBroker Coordination Service is a distributed coordination system, it's a part of an AI ​​Ops platform for self healing. When a moving part in the cloud infrastructure fails, multiple self recovery modules may be triggered at the same time, which result in conflict. For example, several module will try to recover a same database. ZBroker is based on zookeeper and uses a custom read-write lock to resolve these conflicts.

I am responsible for the design and development of this service.

__Bug Auto Triage__ (Python/Bash)

Oracle Operation team file a bug for triage when any failure occurs, 40% of these failures were known issues such as hardware failures, software bugs, or incorrect configuration. This project while a modular framework that analyzes the bug description, attachments, call stacks, and generate a report showing the similarity with other known bugs.

I designed and developed the framework, also implemented the hardware fault module.

### Sykbility

__Skybility High Availability & Disaster Recovery__ (C/Bash)

Skkybility HADR is a Disaster Recovery solution based on a existing two-node High Availability cluster, and integrates open source solution DRBD(similar to a RAID-0 over network) for disaster recovery. To mitigate the performance impact caused by limited internet bandwidth, a proxy module were developed to cache its I/O traffic, and send to its peer asynchronously.

I am responsible for the development of Web Configuration Server, and part of the proxy server.


## Personal Projects

[Live Sequence Protocol](http://code.poetpalace.org/cgit/p1/tree) (Golang): a transport protocol build on top of UDP, implemented some TCP-like features, including sliding window, retransmission, heartbeat, and delivery order.

[Iputils](http://git.poetpalace.org/cgit.cgi/iputils/tree) (Python): a very simple implementation of tcpdump, ping, and traceroute.

[libwp](http://git.poetpalace.org/cgit.cgi/libwp/tree) (C): wrapper for the most common libc, linux, and POSIX function, also contain some frequently used data structures and sorting algorithms.

## Articles (Chinese)

Multiple articles published on [WeChat Public Account](https://cloud.tencent.com/developer/column/79283) 

Comment for [ETCD Raft implementation](https://github.com/4179e1/etcd/tree/master/contrib/raftexample/doc)

A Lecture about [PAXOS, the Distributed Consensus Protocol](http://t.poetpalace.org/misc/paxos.pptx)

Translation of *Randy Meyers'* [The New C](http://misc.poetpalace.org/C99/), which introduce features of C99

## Education

`Sep 2004 – Jul 2009`
**Shenzhen University**

Bachelor of Engineering in Computer Science

## Certificates

`Apr 2020`
__Tencent Cloud Solutions Architect Associate Engineer__

`Aug 2010`
__Red Hat Certified Engineer (RHEL5)__

`Jun 2006`
__College English Test Band 4__


<!-- ### Footer

Last updated: May 2013 -->