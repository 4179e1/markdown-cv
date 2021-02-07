---
layout: cv
title: Yong Li's CV

---
# Yong Li (李勇)

<div id="webaddress">
+86 18927406823 | 
<a href="s4179e1@msn.com">s4179e1@msn.com</a> |
<a href="./YongLi-CV.pdf">Download PDF</a> |
<a href="./zh-cn.html">Chinese Version</a>
</div>

## Specialization

Years of development experience on Linux,

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
**Enterprise IT [Hybrid Role]**

Provide technical solution and consultant service while migrating IT service to Tencent Cloud, especially for containerized services based on Kubernetes & Istio.

Implement Site Reliability Engineering to improve service quality, including procedure, automation, and culture.

Participant in development of Business Group’s R&D platform to improve the productivity of software R&D lifecycle.

`Dec 2018 – Nov 2019`
**Cloud Foundation Department [Software Engineer]**

Responsible of the development of CI/CD system, to support the Tencent cloud infrastructure, including block storage, database, and finance technology.

Lead the development of RolesDB (a configuration management system, see project description below)

`Feb 2018 – Nov 2018`
**Cloud Foundation Department [Site Reliability Engineer]**

Responsible for the operation of Tencent Cloud Block Storage, ensure its availability and reliability

Standardize the operation procedure, leverage CI/CD pipeline to upgrade existing clusters

Developed system to automate new cluster deployment, by bridging gaps between multiple upstream systems.

### Oracle
`Nov 2016 – Feb 2018` **Architecture and Performance Service [Site Reliability Engineer]**

Provide solutions and technical support for Oracle’s infrastructure, participate in the development of AI Ops platform to ensure service reliability.

Join on call rotation to support Oracle production environment, including public cloud. Responsible for critical service recovery and root cause analysis for Oracle Linux, Oracle VM, and ZFS Storage.

`Oct 2012 – Oct 2016`
**Global Support Center [Technical Support Engineer]**

Provide technical support for Oracle Linux and Oracle VM, including but not limited to troubleshooting, crash root cause analysis, and performance tuning.

Problem Management: Respond and solve customers’ problem according to severity level and SLA, escalate and engage more resource if needed.

Knowledge Management: maintain testing environment to reproduce customers problem. Delivered multiple notes in knowledge base.

### Skybility
`May 2010 – Sep 2012`
**Research & Development Center [Software Engineer]**

Skybility is a system integration provider, focus at HA Cluster, Virtualization, and IT services.

Participate in development of multiple products, including High Availability Cluster and Disaster Recovery system, Linux based thin client system, etc.

Participate in the development of open source project [php-libvirt](https://libvirt.org/git/?p=libvirt-php.git;a=search;s=Lyre;st=author) and integrate it into Skybility’s heterogeneous virtualization management platform.

## Projects

### Tencent
__Enterprise IT Container Platform__ (Helm/Golang)

While migrating our containerized applications to Tencent Kubernetes Engine, we integrate it with multiple internal service for access control, namespace isolation, etc. As a Solution Architecture I lead the building of this platform, developed the procedure and best practice in application migration and deployment.

As a Consultant, I share the knowledge on docker and kubernetes via lectures, trainings, demos, and articles. I also responsible for migrating our critical services like IAM into kubernetes.

As a developer, I created a Helm Chart template (which implemented our best practice) and CI/CD plugin to simplify application deployment.

__Enterprise IT Linux Base Image__ (Bash/Golang)

As a part of Site Reliability Engineering, we deliver our standard runtime by creating a Linux Base image. A modular framework were developed to automate the image creation, as well as daily routine inspections to discover the non-standard configuration for online systems.

I purposed these configuration and best practice, developed the scripts to build Linux images, as well as the dashboard for routine inspections.

__RolesDB__ (Python Flask/MongoDB)

RolesDB is an Instance and Configuration Management System, aim to support the CI/CD pipeline for large scale underlying cloud infrastructure (storage, load balancer, etc). Its label based implementation allow user organize instance easily while  filter them preciously.

I am the architecture and lead programmer for this project.

__Cloud Block Storage Deployment__ (Python Flask/ETCD)

This project bridged gaps between multiple upstream services to automate custer deployment, reducing the time to deploy a cluster from 30 minutes (in an ideal condition) to 5 minutes at average. It greatly improve the productivity as we were deploying new clusters every day.

I designed and implemented the whole system.

### Oracle

__Zbroker Coordination Service__ (Python/Zookeeper)

ZBroker Coordination Service is a distributed coordination system, it's a part of an AI ​​Ops platform for self healing. When a moving part in the cloud infrastructure fails, multiple self recovery modules may be triggered at the same time, which result in conflict. For example, several module will try to recover a same database. ZBroker is based on zookeeper and uses a custom read-write lock to resolve these conflicts.

I am responsible for the design and development of this service.

__Bug Auto Triage__ (Python/Bash)

Operation team file bugs for triage whenever components failure, 40% of these bugs were known issues such as hardware failures, software bugs, or incorrect configuration. This project provide a modular framework that analyzes the bug description, attachments, call stacks, and generate a report showing the similarity with other known bugs.

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

Multiple articles published on [WeChat Public Account](https://cloud.tencent.com/developer/column/79283), in a variety of technical fields.

Comment for [ETCD's Raft implementation](https://github.com/4179e1/etcd/tree/master/contrib/raftexample/doc)

A Lecture on distributed system, specially for [PAXOS, the Distributed Consensus Protocol](http://t.poetpalace.org/misc/paxos.pptx)

Translation of *Randy Meyers'* [The New C](http://misc.poetpalace.org/C99/), which introduce features of C99

## Education

`Sep 2004 – Jul 2009`
**Shenzhen University**

Bachelor of Engineering in Computer Science

## Certificates

`Jan 2021`
__AWS Certified Solutions Architect – Associate__

`Apr 2020`
__Tencent Cloud Solutions Architect Associate Engineer__

`Aug 2010`
__Red Hat Certified Engineer (RHEL5)__

`Jun 2006`
__College English Test Band 4__

<!-- ### Footer

Last updated: Jan 2021 -->