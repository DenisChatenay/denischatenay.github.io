---
layout: post
title: Backup and encrypt a MySQL database daily on GNU/Linux
category: Backup
description: Backup a MySQL database daily and encrypt it with GPG GNU/Linux
author: Denis Chatenay
tags: [backup]
---

## 1. Introduction

This tutorial will demonstrate you how to setup a secure daily backup for your MySQL database.

For that, we are going to use the following tools  :

* **Mysqldump** :
* **Bzip2** :
* **GNU Privacy Guard (GPG)** : 

The following diagram represents the communication process and shows how the cluster stack software fits between the service layers :

<p align="center">
  <img src="https://raw.githubusercontent.com/denischatenay/denischatenay.github.io/master/images/posts/cluster/cluster_stack_diagram.png" alt="cluster_stack_diagram" />
</p>

## 2. Goal

**Let me know in comment if there is any issue, mistake... Thanks !**

## Stuff used to make this:

 * Website : [markdown-it](https://github.com/markdown-it/markdown-it) for Markdown parsing
